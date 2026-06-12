# Portfolio — 柯昆緯 Kun-Wei Ko

個人介紹頁，以「建築圖紙」風格設計的單頁網站。

## 內容

- **現職** — HC 鴻騏建設有限公司（副理），含公司聯絡資訊
- **學歷** — 大同大學電機工程碩士、崑山科技大學房地產開發與管理碩士
- **興建建案** — [初居 3](https://newhouse.591.com.tw/139690)（台南歸仁）
- **開發專案** — [台南市不動產分析](https://tainan-realestate-ai.vercel.app/)（實價登錄 × AI）等

## 技術

- 純靜態單頁（`index.html`），無框架、無建置流程
- 設計：工程圖紙風格 — 紙感方格底紋、圖框、標題欄（title block）、區段編號
- 響應式：桌機 / 手機自動調整版型
- 部署：Firebase Hosting

## 本機預覽

```bash
# 在專案根目錄執行
python3 -m http.server 5173
# 瀏覽 http://localhost:5173
```

## 部署

```bash
firebase deploy
```
