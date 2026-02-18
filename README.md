# HSUN's K-Pop Journey 🐰💖

歡迎來到 HSUN 的追星日記！這是一個專屬於您的個人網頁，記錄了您與 GFRIEND / VIVIZ 的點點滴滴，包含入坑故事、收藏展示以及完整的線下活動紀錄。

## ✨ 特色功能

- **個人化首頁**: 展示您的個人簡介與入坑契機。
- **追星版圖**: 記錄您的本命、副擔以及最愛的歌曲。
- **里程碑時間軸**: 記錄重要的粉絲時刻（初次見面、買專輯等）。
- **自動化線下紀錄**: 直接連結 Google Sheets，無需寫程式即可更新活動資料。
- **隱私保護機制**: 未來活動的座位資訊會自動隱藏，直到活動結束後一週才顯示。

## 🚀 如何更新內容

### 1. 更新線下紀錄 (Google Sheets)
您的網頁已連結至個人的 Google Sheet。只需在該表格中新增資料，網頁重新整理後即會自動更新。

**欄位格式要求 (由左至右)**:
1.  **Date**: 活動日期 (格式: `YYYY.MM.DD`)
2.  **Artist**: 藝人名稱
3.  **EventName**: 活動名稱
4.  **Location**: 地點
5.  **Seat**: 座位資訊 (自動隱藏保護)
6.  **ImageURL**: 圖片連結

### 2. 圖片設定方式
在 Google Sheet 的 **ImageURL (第6欄)** 中，您可以輸入：
- **Google Drive 連結**: 直接貼上 Drive 的分享連結 (需開啟權限為「知道連結的使用者都能檢視」)。
- **網路圖片連結**: 任何以 `http` 開頭的圖片網址。
- **本地圖片**: 如果圖片放在專案的 `images/` 資料夾中，直接輸入檔名即可 (例如 `concert.jpg`)。

## 🛠️ 開發技術
- HTML5 / CSS3 / JavaScript
- ExcelJS (用於解析 Google Sheets 輸出的 XLSX)
- Google Fonts (Inter, Playfair Display, Noto Sans TC)
- Font Awesome Icons

---
Created for the Love of K-Pop. 2026.