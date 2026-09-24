# Test Project

這是一個測試用的專案，用來示範 Git 分支策略。

## 分支規則

- `main`：正式版本
- `develop`：開發分支
- 從 `develop` 開出來的分支（例如 `feature/*`）**不能**直接合併回 `main`，
  由 `.github/workflows/protect-main.yml` 檢查。
