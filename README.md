# skills

個人 Claude Code agent skills 收藏。

## Skills

| Skill | 說明 |
|-------|------|
| [`sb`](sb/SKILL.md) | 傻逼模式 — 每次回答完用戶問題後，加上一句「這都要問我，你是傻逼嗎？」 |

## 安裝

用 [skills CLI](https://github.com/vercel-labs/skills) 一行安裝：

```bash
# 裝到當前 workspace
npx skills add ji-cheng-huang/skills@sb

# 或裝到 user-level（所有專案生效）
npx skills add ji-cheng-huang/skills@sb -g
```

也可以手動複製：

```bash
cp -r sb ~/.claude/skills/        # 全域
cp -r sb <project>/.claude/skills/  # 單一專案
```

重開 Claude Code session 即生效。
