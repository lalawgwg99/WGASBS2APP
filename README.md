# 雙識圖 (Double Vision Portal)

這是一個整合兩個訂單識別系統的入口網頁。

## 功能

- **手機訂單識別**: 連接至 `https://phonesbs.pages.dev/`
- **廚房三機識別**: 連接至 `https://wga3g.pages.dev/`
- **特色**:
  - 特斯拉風格 (Tesla-style) 深色介面
  - 科技線圖流動背景 (Canvas Animation)
  - 玻璃擬態設計 (Glassmorphism)

## 部署至 Cloudflare Pages

1. 登入 [Cloudflare Dashboard](https://dash.cloudflare.com/)。
2. 進入 **Workers & Pages** > **Create application** > **Pages** > **Connect to Git**。
3. 選擇此倉庫 `WGASBS2APP`。
4. **Build settings** (建置設定):
    - **Framework preset**: `None` (無)
    - **Build command**: (保持空白)
    - **Build output directory**: `.` (或者 `/`)
5. 點擊 **Save and Deploy**。

## 本地開發

直接用瀏覽器打開 `index.html` 即可預覽。
