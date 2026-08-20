# 鹿鹿走讀轉進南湖東峰 · GPX 路徑整合圖

2026.08.13–08.18，南湖群峰縱走 28 個 GPX 檔去重整合後的互動地圖。
6 天 · 60 公里 · 累積上升 9,681 公尺 · 最高 3,643 公尺。

## 上傳到 GitHub Pages

1. 建一個新的 repository（設為 Public）。
2. 把這個資料夾裡的三個檔案上傳到 repo 根目錄，三個必須放在同一層：

   - `index.html`
   - `support.js`
   - `trip.json`

3. 進 repo 的 **Settings → Pages**，Source 選 **Deploy from a branch**，
   Branch 選 `main` + `/ (root)`，按 Save。
4. 等一兩分鐘，網址是 `https://<你的帳號>.github.io/<repo 名稱>/`。

## 注意事項

- 需要連網：字體、Leaflet、地形圖磚都來自 CDN。
- 底圖為內政部國土測繪中心「通用版電子地圖」（繁體中文山名、等高線、山徑）。
- 目前版面是桌機寬螢幕設計，建議 1000px 以上；手機版另外處理。
