# 會議重點整理｜新任執行副總 許純琪

這是一份可直接部署到 GitHub Pages 的單頁式會議重點整理網頁。

## 專案結構

```text
.
├── index.html      # GitHub Pages 首頁
├── README.md       # 專案說明
├── .nojekyll       # 避免 GitHub Pages 進行 Jekyll 處理
└── .gitignore      # 忽略系統暫存檔
```

## 如何上傳到 GitHub Pages

1. 在 GitHub 建立一個新的 repository。
2. 將本資料夾內的所有檔案上傳到 repository 根目錄。
3. 到 repository 的 **Settings → Pages**。
4. Source 選擇 **Deploy from a branch**。
5. Branch 選擇 **main / root**。
6. 儲存後，等待 GitHub Pages 產生網址。

## 本頁特色

- 單檔 `index.html`，CSS 與 JavaScript 已內嵌。
- 可直接作為 GitHub Pages 首頁。
- 手機、平板、桌機響應式排版。
- 使用原生 `details` 摺疊元件，手機瀏覽穩定。
- 列印時 Q&A 內容會完整展開。

## 建議 repository 名稱

```text
judy-meeting-summary
```

或：

```text
fubon-meeting-judy-summary
```
