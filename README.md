# 2026 下半年 KPI 追蹤

依與主管共識之權重列出各項行動計畫，完成後打勾即可。涉及多專案的項目拆成子項目分別追蹤進度。佐證檔案／連結放在 [`2026/H2/evidence/`](2026/H2/evidence/) 對應子資料夾。

## 提升程式開發與測試效率與品質 30%

### 時程掌握
- [ ] 每月更新「預估 vs 實際時數差異」表，部門總時程誤差 < 25%、主管預估與個人預估誤差 < 20% — [佐證](2026/H2/evidence/hours-tracking/)
- [ ] 將延誤原因分類（開發／測試／需求變更）並建立改善措施；工時紀錄需列出卡關點，搭配工時分析報告循環檢討

### 擴大測試自動化覆蓋範圍
- [ ] 建立測試案例撰寫規範並回饋知識庫，延續上半年排序測試寫法分享，說明寫法差異與原因
- [ ] 擴展 Playwright E2E 測試案例，涵蓋登入、權限、主流程操作 — [佐證](2026/H2/evidence/test-automation/)

### 品質數據化管理
- [ ] 透過 redmine 測試與客訴議題的既有原因分析，固定頻率覆盤與分類 — [佐證](2026/H2/evidence/quality-review/)

## 推動技術創新與自動化 30%

### AI 輔助開發深化應用
- [ ] 延續 task-scope.skill 經驗，將知識庫規範轉化為「寫給 AI 執行」的 Skill（Coding Style 檢查、PR 前 Code Review），下半年至少完成 2 個 skill 開發與推廣 — [佐證](2026/H2/evidence/skills/)
- [ ] 導入「可控性」AI 知識庫，整合多 VM 規範為單一 git 化 repo，產出 1 份「基於 Skill 與 Git 化管理的 AI 知識庫開發實務」 — [佐證](2026/H2/evidence/skills/)

### CI/CD 擴展與落地
- 空專案、AmasPortal、AmasCar 導入 gitLeaks，於 Husky (pre-commit) 及 CI 階段部署自動化機敏資料攔截 (3/3) — [佐證](2026/H2/evidence/gitleaks/)
  - [x] 空專案 — [CI 攔截驗證 PR #35](https://github.com/amassp/empty_project/pull/35)
  - [x] AmasPortal
  - [x] AmasCar — [CI 攔截驗證 PR #14](https://github.com/amassp/AmasCar/pull/14)
- 針對負責之專案進行 gitLeaks history 檢查，盤點過往 commit 是否有敏感資訊殘留 (3/3) — [佐證](2026/H2/evidence/gitleaks/)
  - [x] 空專案（2026/10/05，0 finding）
  - [x] AmasPortal（2026/10/02，0 finding）
  - [x] AmasCar（2026/10/02，1 finding，待確認金鑰是否已撤銷）

### 開發流程優化
- [ ] 環境建置／開發問題排除後回饋於知識庫
- [ ] 每兩個月於前端會議進行技術分享，預計完成 3 場 — [佐證](2026/H2/evidence/tech-sharing/)

## 資訊安全與品質保證 20%

### 持續落實資安檢查
- [ ] 配合公司資安政策與稽核要求完成相關檢查作業
- [ ] 定期檢視專案資安設定與開發流程

### 完善開發標準化流程
- 空專案、AmasPortal、AmasCar 導入 yarn audit，每季執行並以 skill 解析報告，作為版本升級與風險修正決策依據 (0/3) — [佐證](2026/H2/evidence/yarn-audit/)
  - [ ] 空專案
  - [ ] AmasPortal
  - [ ] AmasCar

## 個人能力提升 20%
- [ ] 學習 Vite 打包優化理論，於公務車專案用 rollup-plugin-visualizer 視覺化最大佔比套件
- [ ] 研究 Playwright 冒煙測試怎麼做，以可讀資料、一般按鈕跳轉行為當 MVP，分享冒煙測試的好處 — [佐證](2026/H2/evidence/test-automation/)
- [ ] 研究 rails, vue 對前端效能優化的改善方法
