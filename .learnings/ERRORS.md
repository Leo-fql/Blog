# Errors

Command failures and integration errors.

---

## [ERR-20260415-001] git_config

**Logged**: 2026-04-15T14:40:00+08:00
**Priority**: high
**Status**: resolved
**Area**: infra

### Summary
Git提交失败 - 未配置用户身份

### Error
```
Author identity unknown
*** Please tell me who you are.
Run
  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"
```

### Context
- 在初始化Git仓库并首次提交时发生
- 原因：本地Git未配置用户信息

### Suggested Fix
提交前先配置Git用户信息：
```bash
git config user.email "your@email.com"
git config user.name "Your Name"
```

### Resolution
- **Resolved**: 2026-04-15
- **Notes**: 使用临时配置完成了首次提交

---
