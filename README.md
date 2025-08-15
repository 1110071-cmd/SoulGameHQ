# SoulsGameHQ（高畫質版）— AppVeyor 一鍵打包 Windows EXE

## 使用教學（超簡單）
1. 到 GitHub 建一個空的公開倉庫（例如 `SoulGameHQ`）。
2. 將本 ZIP **解壓後的所有檔案與資料夾**，直接拖曳到倉庫根目錄上傳（不是整個資料夾）。
3. 到 AppVeyor (appveyor.com) → New Project → 連結你的 GitHub → 選這個倉庫 → Add。
4. 在 AppVeyor 專案頁按 **New build**。等待完成後，去 **Artifacts** 分頁下載 `.exe`。

## FAQ
- 若 Build 失敗，請確認：
  - `appveyor.yml`、`package.json` 在倉庫根目錄。
  - 倉庫是 Public 或 AppVeyor 有權限讀取。
  - 重按一次 **New build**。
