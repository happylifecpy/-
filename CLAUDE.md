# eatwhat_ncu 專案規則

## 分支策略
- **永遠直接在 `main` 分支開發**，不建立 feature branch
- 所有 commit 和 push 都推到 `main`

## 版本號規則
- 每次修改 `index.html` 後，更新頁面右下角的版本號
- 版本格式：`v主版本.次版本`（例如 `v1.0`、`v1.1`）
- 功能新增或 bug 修正：次版本 +1（v1.0 → v1.1）
- 大幅改版：主版本 +1，次版本歸零（v1.1 → v2.0）
- 版本號位於 `index.html` 的 `<span id="app-version">` 元素內
