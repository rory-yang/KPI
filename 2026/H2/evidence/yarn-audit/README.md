# yarn audit 報告

各專案的相依套件漏洞掃描結果，用於佐證「完善開發標準化流程」項目。

- 每次掃描存一份報告：`yarn-audit-report-<YYMMDD>.pdf`（由 skill 解析 `yarn audit --json` 產出的 HTML 報告，以「下載完整 PDF（含附錄）」匯出）
- 各專案資料夾的 README 記錄每次掃描的結論（Advisory 數、A–D 分類、待辦）
- 掃描指令：

```bash
yarn audit --json > audit.json
# yarn berry 用：yarn npm audit --json > audit.json
```

## 進度

| 專案 | 最近一次掃描 | 報告 |
|---|---|---|
| 空專案 | 尚未執行 | — |
| AmasPortal | 2026/11/12 | [yarn-audit-report-261112.pdf](AmasPortal/yarn-audit-report-261112.pdf) |
| AmasCar | 尚未執行 | — |
