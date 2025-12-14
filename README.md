# 個人簡歷網頁專案

這是我的個人簡歷網頁設計作業，包含個人資訊、技能展示、經歷時間軸與作品集。

## 專案網址
[點擊這裡瀏覽我的網站](https://414570289chiu.github.io/Demo/)

## 作業要求說明

### 1. 關於 Git Revert
我在開發過程中曾嘗試加入一段測試代碼（commit: `chore: error code`），但發現不符需求，就使用 `git revert` 指令將其復原，以保持版本紀錄的完整，而沒有直接刪除commit。

### 2. 關於 A/B Test
我建立了一個分支 `feature/ab-test` 來測試不同的排版效果。
- **Main 分支 (Version A)**：採用目前的穩定版面設計。
- **Feature 分支 (Version B)**：嘗試了不同的技能展示方式。
經過評估，我決定保留main分支的設計作為最終版本，因此 `feature/ab-test` 的 Pull Request 保持（Unmerged）讓老師看差異。