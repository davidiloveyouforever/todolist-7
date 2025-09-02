# 📱 待辦事項清單 PWA

一個功能完整的待辦事項管理應用程式，支援 PWA (Progressive Web App) 功能，可以安裝在手機主畫面上。

## 🚀 線上版本

**GitHub Pages 部署**: [https://davidiloveyouforever.github.io/todolist-6/](https://davidiloveyouforever.github.io/todolist-6/)

## 📋 功能特色

### 基本功能
- 📝 **新增待辦事項**：支援100則記事
- 🎨 **顏色分類**：8種顏色可選擇
- 📅 **日期管理**：按日期排序和過濾
- ✅ **完成標記**：一鍵標記完成/未完成
- ✏️ **編輯功能**：可修改內容、日期和顏色

### 分類瀏覽
- 📅 **今天**：查看今天的待辦事項
- 📆 **本週**：查看本週的待辦事項
- 📋 **全部**：查看所有待辦事項
- ⚠️ **過期**：查看已過期但未完成的項目

### PWA 專屬功能
- 📱 **安裝到主畫面**：一鍵安裝APP
- 🔄 **離線使用**：無網路也能正常使用
- 📊 **進度追蹤**：視覺化顯示完成進度
- 📤📥 **資料匯出/匯入**：備份和還原資料
- 🎯 **快速操作**：滑動切換、快捷鍵支援

## 🛠️ 技術架構

- **前端**: HTML5, CSS3, JavaScript (ES6+)
- **PWA**: Service Worker, Web App Manifest
- **儲存**: localStorage
- **部署**: GitHub Pages

## 📁 檔案結構

```
todolist-6/
├── index-simple.html      # 主要HTML檔案 (PWA版本)
├── script-simple.js       # JavaScript邏輯
├── styles.css            # CSS樣式
├── manifest.json         # PWA設定檔
├── sw.js                # Service Worker
├── icons/               # PWA圖示
│   ├── icon-16x16.png
│   ├── icon-32x32.png
│   ├── icon-72x72.png
│   ├── icon-96x96.png
│   ├── icon-128x128.png
│   ├── icon-144x144.png
│   ├── icon-152x152.png
│   ├── icon-180x180.png
│   ├── icon-192x192.png
│   ├── icon-384x384.png
│   └── icon-512x512.png
├── create-icons.html     # 圖示生成工具
├── test-simple.html     # 簡化測試版本
├── README.md           # 專案說明
└── README-PWA.md       # PWA安裝指南
```

## 🚀 本地開發

### 1. 克隆專案
```bash
git clone https://github.com/davidiloveyouforever/todolist-6.git
cd todolist-6
```

### 2. 啟動本地伺服器
```bash
python -m http.server 8000
```

### 3. 開啟瀏覽器
```
http://localhost:8000/index-simple.html
```

## 📱 PWA 安裝指南

### Android (Chrome)
1. 開啟網頁
2. 點擊瀏覽器的「安裝」按鈕
3. 確認安裝

### iPhone (Safari)
1. 開啟網頁
2. 點擊「分享」按鈕
3. 選擇「加入主畫面」

## 🔧 部署到 GitHub Pages

### 1. 建立 GitHub 倉庫
```bash
git init
git add .
git commit -m "Initial commit: Todo List PWA"
git branch -M main
git remote add origin https://github.com/davidiloveyouforever/todolist-6.git
git push -u origin main
```

### 2. 設定 GitHub Pages
1. 前往 GitHub 倉庫設定
2. 找到 "Pages" 選項
3. 選擇 "Deploy from a branch"
4. 選擇 "main" 分支和 "/ (root)" 資料夾
5. 點擊 "Save"

### 3. 等待部署完成
GitHub Pages 會自動部署您的專案到：
`https://davidiloveyouforever.github.io/todolist-6/`

## 🎮 使用說明

### 基本操作
1. **新增待辦事項**：在輸入框中輸入內容，選擇日期和顏色，點擊「新增」
2. **完成待辦事項**：點擊記事旁的圓圈按鈕 (○)
3. **編輯待辦事項**：點擊記事旁的編輯按鈕 (✎)
4. **刪除待辦事項**：點擊記事旁的垃圾桶按鈕 (🗑)

### 手機操作
- **滑動切換分類**：左右滑動可切換「今天」、「本週」、「全部」、「過期」
- **快速操作**：使用底部的快速操作按鈕

### 快捷鍵 (電腦版)
- `Ctrl + 1`：切換到「今天」
- `Ctrl + 2`：切換到「本週」
- `Ctrl + 3`：切換到「全部」
- `Ctrl + 4`：切換到「過期」

## 🔍 故障排除

### 無法安裝 PWA
- 確認瀏覽器支援 PWA
- 檢查是否使用 HTTPS (GitHub Pages 自動提供)
- 確認 manifest.json 設定正確

### 離線功能異常
- 檢查 Service Worker 是否註冊成功
- 清除瀏覽器快取後重新載入

### 圖示不顯示
- 確認圖示檔案存在且路徑正確
- 清除瀏覽器快取

## 📞 支援

如果遇到問題，可以：
1. 檢查瀏覽器控制台錯誤訊息
2. 清除快取後重新載入
3. 重新安裝 PWA
4. 使用不同瀏覽器測試

## 📄 授權

本專案採用 MIT 授權條款。

## 🤝 貢獻

歡迎提交 Issue 和 Pull Request！

---

**版本**: v1.2  
**更新日期**: 2024年  
**作者**: David  
**技術**: HTML5, CSS3, JavaScript, PWA
