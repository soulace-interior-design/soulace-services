# soulace-services

Soulace Interior 專案的後端服務總覽，給非技術背景的使用者看。

一頁說明六個服務各自做什麼、誰是 Owner / Admin、付費狀態，以及該用哪個按鈕登入。

線上版本：GitHub Pages（見 repo 的 Settings → Pages）

## 技術

單一 `index.html`，手寫 CSS，零建置、零相依。只有字體從 Google Fonts 載入。

刻意不用建置工具：這頁的更新頻率極低（接自訂網域時才會動一次），任何建置步驟或套件相依在半年後都會腐壞而且沒人會發現。

頁面分兩個分頁籤：「服務架構」（預設）與「客戶流程」。網址加 `#flow` 可直接開到客戶流程（`#architecture` 為服務架構）。JS 沒執行時兩塊內容會同時顯示。

## 視覺

刻意**不**沿用 Soulace 官網的設計系統（酒紅 / 金 / Cormorant Garamond）。這是一份參考工具頁，不是行銷頁，採用深色開發者工具的視覺語言以利閱讀。這是決定，不是疏漏——請勿「順手修正」回官網那套。

## 維護注意

- 架構圖裡的「後台連結」按鈕目前硬編碼指向 `soulace-interior.fly.dev/admin`。接上自訂網域後這裡要改。
- 服務 logo 來自 Simple Icons（專案本身 CC0），各品牌標誌仍為其擁有者之商標。
- 品牌色分深淺兩套：Fly.io、Resend、GitHub 的官方色在深色底上不可見，深色模式改用可讀版本。
