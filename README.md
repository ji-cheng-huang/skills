# skills

個人 Claude Code agent skills 收藏。

## Skills

| Skill | 說明 |
|-------|------|
| [`sb`](sb/SKILL.md) | 傻逼模式 — 每次回答完用戶問題後，加上一句「這都要問我，你是傻逼嗎？」 |

## 安裝

把想要的 skill 資料夾複製到 Claude Code 的 skills 目錄：

```bash
# 全域安裝（所有專案生效）
cp -r sb ~/.claude/skills/

# 或只裝在某個專案
cp -r sb <project>/.claude/skills/
```

重開 Claude Code session 即生效。
