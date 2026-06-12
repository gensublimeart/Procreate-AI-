# Procreate及AI生圖工作坊

香港社福服務專業培訓教材包，以繁體中文製作。

## 內容

| 檔案 | 說明 |
|------|------|
| `index.html` | 工作坊首頁 |
| `slides.html` | 簡報（Marp 全螢幕投影片） |
| `worksheet.html` | 學員工作紙（互動版） |
| `worksheet.pdf` | 學員工作紙（可列印 PDF） |
| `online_note.html` | 網上筆記（互動式學習頁面） |
| `slides.md` / `worksheet.md` | 原始 Markdown 來源檔 |

## 部署至 GitHub Pages

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

使用任何靜態伺服器即可預覽，例如：

```bash
cd For_Github
python -m http.server 8080
```

然後開啟 http://localhost:8080

## 授權

© 2026 GenSublime
