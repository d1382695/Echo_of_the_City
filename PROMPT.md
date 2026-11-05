# Vibe Coding 開發指令與 Prompt 說明文件

- **專案名稱**：大三學期專題 — 「都心迴響」影展專題介紹網站
- **作者**：曾千懿 (學號：D1382695)
- **學校**：逢甲大學

---

## 💡 AI Vibe Coding 提示詞 (Prompts) 紀錄

本專案採用 **Vibe Coding** 人工智慧輔助模式進行開發，針對「都心迴響」主題進行提示詞設計：

### Prompt 1：核心主題與文案融入
> **提示詞：**
> 「我的大二影展主題是《都心迴響》，內容為探討空氣品質與永續發展，並以搭乘台中電動公車慢遊台中、品嚐在地味道、聆聽城市心跳聲為核心。請將此主題融入 HTML5 語意網頁結構中。」

### Prompt 2：YouTube 嵌入碼整合與 HTML5 規範
> **提示詞：**
> 「請幫我將 YouTube 嵌入碼 `<iframe width="560" height="315" src="https://www.youtube.com/embed/cYB2IQ08Wrs?si=wrgn6HzdJlijYE01" ...></iframe>` 整合至網頁中，並清理過時屬性，確保符合 HTML5 與 RWD 縮放標準。」

### Prompt 3：CSS 檔案切割與 Grid 雙欄排版
> **提示詞：**
> 「請將 CSS 切割為 `css/grid.css` (負責 CSS Grid 主欄 3 份 + 側邊欄 1 份與 @media 768px 降階) 及 `css/style.css` (負責永續綠意配色、標題邊框、卡片陰影與 Pagination 分頁)。」

---

## 🛠️ 技術優化細節
1. **RWD 手持裝置相容性**：在 `768px` 寬度下自動將雙欄切換為單欄，確保行動裝置瀏覽順暢。
2. **SEO & OG 社群標籤**：完整補齊 description、author (曾千懿)、og:title、og:image 等卡片資訊。
