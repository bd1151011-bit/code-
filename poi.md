# 何沐宸 - 個人作品集與履歷網站 (Personal Portfolio Website)

這是一個為**何沐宸**（開南大學資訊管理學系）設計的單頁式響應式個人作品集網站。網站採用極簡、清晰的現代風格設計，完美切合「簡單生活、認真對待每件事」的個人座右銘與品牌形象。

## 📌 網站核心功能 (Features)

1. **首頁 / 個人介紹 (Hero Section)**

   * 品牌標頭與開南資管系身分標籤。

   * 醒目的個人座右銘與極簡視覺風格。

   * 快速導覽與聯繫按鈕。

2. **關於我 (About Me)**

   * **互動相片區塊**：支援本機圖片點擊上傳與即時預覽功能，方便自由更換個人大頭照。

   * 詳細的個人特質介紹與生活哲學說明。

3. **技能展示 (Skills)**

   * 視覺化展示三項核心專長：

     * 💻 **寫代碼 / 程式開發** (Software Development)

     * 📐 **微積分 / 數理分析** (Calculus & Mathematics)

     * 🌐 **資訊管理與系統思維** (Information Systems)

   * 搭配動態進度條呈現個人技能熟練度與專注度。

4. **聯繫方式 (Contact & Socials)**

   * 整合三大聯絡管道（Email、Line、Instagram）。

   * **一鍵複製功能**：點擊圖示即可直接將 Email 或帳號複製至剪貼簿，並彈出優雅的通知提示（Toast notification）。

   * **互動發送訊息表單**：提供訪客直接填寫姓名、Email 與留言訊息的快速介面。

5. **全響應式設計 (Responsive Design)**

   * 支援桌上型電腦、平板與手機等各種螢幕尺寸。

   * 手機版具備漢堡選單（Hamburger Menu）導覽功能。

## 🛠️ 使用技術 (Tech Stack)

* **前端標籤/結構**：HTML5 (語意化標籤)

* **樣式與排版**：[Tailwind CSS](https://tailwindcss.com/) (經由 CDN 載入，包含自訂顏色與現代玻璃擬態特效)

* **圖示庫**：[FontAwesome 6.4.0](https://fontawesome.com/)

* **字型**：Google Fonts (Inter & Noto Sans TC)

* **邏輯與互動**：原生 JavaScript (Vanilla JS)

  * 相片上傳預覽 (FileReader API)

  * 剪貼簿複製 (execCommand / Clipboard)

  * Toast 彈跳通知控制

  * 手機版導覽選單切換

## 📂 專案檔案結構 (Project Structure)

```
├── index.html        # 主網頁檔案（包含 HTML、Tailwind CSS 樣式與 JS 邏輯）
└── README.md         # 專案說明文件

```

## 🚀 如何使用與執行 (Usage)

1. 將 `index.html` 檔案下載至本機電腦。

2. 雙擊 `index.html` 檔案，即可直接在任何主流瀏覽器（Google Chrome, Edge, Safari, Firefox 等）中開啟並檢視網站。

3. 部署方式：可直接上傳至 GitHub Pages、Vercel 或 Netlify 等靜態網頁託播平台，完全無需額外建置（Build）步驟。

## ✉️ 個人聯絡資訊 (Contact)

* **姓名**：何沐宸 (He Muchen)

* **學校**：開南大學 資訊管理學系

* **Email**：`bd1151011@vnus.lit.edu.tw`

* **Line**：何沐宸

* **Instagram**：`watharinsaeher`