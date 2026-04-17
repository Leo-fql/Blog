# Feature Requests

Capabilities requested by the user.

---

## [FEAT-20260415-001] nav_anchor

**Logged**: 2026-04-15T14:40:00+08:00
**Priority**: medium
**Status**: resolved
**Area**: frontend

### Requested Capability
导航菜单中的"博客文章"链接应锚定到首页文章区域，而非跳转独立列表页

### User Context
用户希望导航体验与"个人项目"一致，点击后平滑滚动到首页对应板块，而不是打开新页面

### Complexity Estimate
simple

### Suggested Implementation
将 `href="articles/list.html"` 改为 `href="#articles"`，确保首页有对应id的文章板块

### Resolution
- **Resolved**: 2026-04-15
- **Commit**: 781f9ff
- **Notes**: 已修改首页导航链接指向 #articles

---
