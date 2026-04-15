# Learnings

Corrections, insights, and knowledge gaps captured during development.

**Categories**: correction | insight | knowledge_gap | best_practice

---

## [LRN-20260415-001] correction

**Logged**: 2026-04-15T14:40:00+08:00
**Priority**: medium
**Status**: resolved
**Area**: config

### Summary
文章列表页HTML中出现字面 `\n` 字符而非真正的换行

### Details
在 `articles/list.html` 第144行，导航菜单项之间出现了字面的 `` `n `` 字符。这通常是在编辑文件时使用了字符串拼接或模板错误导致的。

### Suggested Action
编辑HTML文件时，确保使用真正的换行符而不是转义字符

### Metadata
- Source: error
- Related Files: articles/list.html
- Tags: html, nav, bug

---
