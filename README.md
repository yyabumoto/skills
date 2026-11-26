# skills

個人用の Agent Skills。[gh skill](https://cli.github.com/manual/gh_skill) でインストール・更新する。

| スキル | 内容 |
|---|---|
| [migiude](skills/migiude/SKILL.md) | AI と一緒にソフトウェアを開発するためのフロー |

## インストール

```bash
gh skill install yyabumoto/skills migiude --agent universal --scope user
```

`--agent universal --scope user` は `~/.agents/skills` に置く。Claude Code など別のエージェントに入れる場合は `--agent` を変える。

## 更新

```bash
gh skill update --all
```

## スキルの追加・変更

`skills/<name>/SKILL.md` に置く。push する前に検証する。

```bash
gh skill publish --dry-run
```
