本專案採用雙 AI 流程：

1. Codex 負責設計、實作與修正。
2. Claude 負責檢查、建議與驗收。
3. Codex 每次修改後必須更新 REVIEW.md。
4. Claude review 後必須回覆 STATUS: PASS 或 NEED_CHANGES。
5. 只有 Claude 回覆 PASS 後，才可以 commit/push/deploy。