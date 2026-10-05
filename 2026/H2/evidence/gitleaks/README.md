# gitLeaks 掃描報告

各專案的 gitLeaks 掃描結果，用於佐證「CI/CD 擴展與落地」項目。

- 每次掃描存一份報告：`gitleaks-report-<YYMMDD>.pdf`
- 掃描指令（預設會涵蓋整個 git history）：

```bash
gitleaks detect --source . --report-format json --report-path report.json
```
