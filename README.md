# Riley Liu - Static Resume Site

這是一個純靜態的履歷網站，已經移除所有 React/npm 依賴，可直接部屬至 GitHub Pages。

## 如何部屬到 GitHub Pages

1. **建立新的 Repository**：
   - 在 GitHub 上建立一個新的儲存庫（例如：`resume`）。

2. **上傳檔案**：
   - 將 `index.html` 直接上傳到該儲存庫的根目錄。

3. **開啟 GitHub Pages 服務**：
   - 進入該儲存庫的 **Settings** 標籤。
   - 在左側選單點選 **Pages**。
   - 在 **Build and deployment** 區塊，確認 Source 是 `Deploy from a branch`。
   - Branch 選擇 `main`（或你上傳的分支），Folder 選擇 `/(root)`。
   - 點擊 **Save**。

4. **完成**：
   - 稍等約 1-2 分鐘，你的履歷網址就會出現在頁面頂端（例如：`https://yourname.github.io/resume/`）。

## 特色
- **100% 靜態**：無需安裝 Node.js 或執行任何 build 指令。
- **列印優化**：內建 A4 列印 CSS，點擊右下角按鈕可直接生成專業 PDF 履歷。
- **RWD**：支援手機與桌機完美顯示。
- **免維護**：不使用 npm 套件，不會有版本過期或路徑 404 的問題。# rileyliu_webresume_202601
