# HOKKAIDO 2026｜北海道冬日旅行手帖

## 本機啟動
```bash
npm install
npm run dev
```

## GitHub Pages 部署
1. 建立 GitHub repository，名稱建議 `hokkaido-2026`。
2. 上傳此專案全部檔案至 repository 根目錄。
3. 若 repository 名稱不同，修改 `vite.config.js` 的 `base: '/hokkaido-2026/'`。
4. GitHub → Settings → Pages → Build and deployment → Source 選 GitHub Actions。
5. 推送到 `main` 後，Actions 會自動建置及部署。
6. 網址格式：`https://你的帳號.github.io/hokkaido-2026/`。

## 內容編輯
- 每日行程：選擇日期，新增／編輯／刪除行程。
- 景點照片：編輯行程，貼上照片網址；餐廳頁也可設定照片網址。
- 地圖：餐廳頁內嵌 OpenStreetMap；行程與餐廳提供 Google Maps 搜尋導航。
- 記帳：日幣／台幣支出，預設匯率 0.22，可自行調整。
- 行李：勾選狀態存在本機瀏覽器。
- 旅行資訊頁可匯出／匯入 JSON 備份。

## 重要
- LocalStorage 只保存在單一瀏覽器，不會跨裝置同步。
- 網站公開，請勿放護照號碼、訂單編號、私人電話等敏感資訊。
- 目前行程沿用先前討論的資訊；「待確認」項目不是已完成預約。
- 景點地圖座標是初始參考值，請在行程編輯介面確認。
