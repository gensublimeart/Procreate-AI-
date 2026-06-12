# GitHub Pages 部署說明

本文件供主辦方參考。學員請閱讀 [README.md](README.md)。

## 部署步驟

### 方法一：以此資料夾作為倉庫根目錄

1. 在 GitHub 建立新倉庫
2. 將 `For_Github` 資料夾內所有檔案推送到倉庫根目錄
3. 前往 **Settings → Pages**
4. 在 **Build and deployment** 下選擇 **Deploy from a branch**
5. Branch 選 `main`，Folder 選 `/ (root)`
6. 儲存後數分鐘內即可透過 `https://<用戶名>.github.io/<倉庫名>/` 存取

### 方法二：作為子資料夾（docs）

若整個專案是一個大倉庫，可將此資料夾內容複製到 `/docs`，然後在 Pages 設定中選擇 Folder 為 `/docs`。

## 本地預覽

```bash
cd For_Github
python -m http.server 8080
```

然後開啟 http://localhost:8080

## 檔案說明

| 檔案 | 說明 |
|------|------|
| `README.md` | 學員首頁（GitHub 倉庫主頁） |
| `index.html` | GitHub Pages 網站首頁 |
| `slides.html` | 簡報 |
| `worksheet.html` | 學員工作紙 |
| `worksheet.pdf` | 可列印 PDF |
| `online_note.html` | 網上筆記 |
