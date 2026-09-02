# yarn audit 報告

各專案的相依性漏洞掃描結果，用於佐證「完善開發標準化流程」項目，每季執行一次。

- 每次掃描存一份原始報告：`<日期>-audit.json`，搭配一份 `<日期>-summary.md` 摘要重點（風險套件、處理狀態）
- 掃描指令：

```bash
yarn audit --json > audit.json
# yarn berry 用：yarn npm audit --json > audit.json
```
