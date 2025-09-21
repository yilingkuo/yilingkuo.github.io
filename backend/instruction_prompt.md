# 後端專案指南 (Node.js with Express)

## 概述

此目錄包含 Node.js 後端 API 的程式碼。

## 啟動開發伺服器

1. 安裝依賴: `npm install` 或 `yarn install`
2. 設定環境變數 (參考 `.env` 檔案)。
3. 啟動伺服器: `npm run dev` (如果使用 nodemon) 或 `node server.js`。
4. API 將在 `http://localhost:3000` (預設) 運行。

## 目錄結構說明

- `config/`: 配置檔案，如資料庫連接、JWT 密鑰。
- `controllers/`: 處理請求邏輯，與模型互動。
- `models/`: 資料庫模型定義。
- `routes/`: API 路由定義。
- `middleware/`: 中間件，如認證、錯誤處理。
- `services/`: 業務邏輯，可重用功能。
- `utils/`: 工具函數。
- `.env`: 環境變數範本。
- `server.js`: 應用程式入口點。
- `package.json`: 專案依賴和腳本。
