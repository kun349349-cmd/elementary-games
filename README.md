# 國小跨領域互動教學遊戲大廳 (Elementary Interactive Learning Games)

專為**小學課堂教學**設計的跨領域單一網頁互動遊戲庫，包含數學領域與國語領域，適配大螢幕智慧觸控電子白板（Smartboard）、iPad / Android 平板與各類瀏覽器。

---

## 📂 專案目錄結構

```text
elementary-games/
├── 📄 index.html                      <-- 🌟【跨學科總首頁】：切換數學館、國語館
│
├── 📁 math/                           <-- 📐 數學領域專區
│   ├── 📄 index.html                  <-- 數學單元目錄大廳
│   └── 📁 1上_L5_方盒圓罐球/           <-- 現有單元五遊戲
│       ├── 📄 index.html              <-- L5 單元首頁
│       ├── 🎮 game1_santa_maze.html   <-- 遊戲 A：聖誕郵筒迷宮大冒險 (P66-67)
│       └── 🏗️ game2_shape_workshop.html <-- 遊戲 B：形狀小工坊 (P68-72)
│
└── 📁 chinese/                        <-- 📖 國語領域專區
    └── 📄 index.html                  <-- 國語單元目錄大廳 (籌備更新中)
```

---

## 🌟 教學特色
1. **單一網址、全科整合**：全校師生只需記住一個 GitHub Pages 網址，未來擴充任何單元皆在同一個網站下。
2. **零安裝、單一網頁檔案**：所有音效、向量圖形與物理引擎皆內嵌於 HTML 檔案中，免架伺服器，甚至支援單檔下載離線遊玩。
3. **台灣微軟神經自然發音（曉臻老師）**：親切溫和的台灣教師咬字，符合小一生聽覺認知。
4. **大按鈕觸控友善**：防誤觸光暈、大卡片佈局，適合學童在電子白板前動手互動。

---

## 🚀 GitHub Pages 快速發布步驟

1. 在 GitHub 建立一個公開倉庫（Repository），命名為 `elementary-games`。
2. 將本資料夾內的所有檔案與資料夾（包含 `index.html`、`math`、`chinese`、`README.md`）上傳至倉庫根目錄。
3. 進入倉庫的 **Settings** ➔ **Pages**。
4. 在 **Build and deployment** ➔ **Branch** 選擇 `main`，資料夾選擇 `/ (root)`，點擊 **Save**。
5. 約等待 1~2 分鐘後，即可透過專屬網址暢玩：
   `https://<你的 GitHub 帳號>.github.io/elementary-games/`
