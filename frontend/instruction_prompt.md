# 前端專案指南 (Vue 3)

## 概述

此目錄包含 Vue 3 前端應用程式的程式碼。

## Vue 3 快速開始

參考 Vue 官方快速開始指南來建立和初始化 Vue 3 專案：
[https://vuejs.org/guide/quick-start.html](https://vuejs.org/guide/quick-start.html)

### 建立專案指令

建議使用 Vite 建立 Vue 專案：

```bash
npm create vue@latest
# 然後依照提示操作
```

## 啟動開發伺服器

1. 安裝依賴: `npm install` 或 `yarn install`
2. 啟動開發伺服器: `npm run dev` 或 `yarn dev`
3. 應用程式將在 `http://localhost:5173` (預設) 運行。

## 目錄結構說明

- `public/`: 靜態資源，如 `index.html`。
- `src/`: 應用程式核心程式碼。
  - `assets/`: 靜態資源，如圖片、CSS 檔案。
  - `components/`: 可重用的 Vue 元件。
  - `views/`: 路由對應的頁面元件。
  - `router/`: Vue Router 配置。
  - `stores/`: Pinia 狀態管理模組。
  - `services/`: API 服務呼叫邏輯。
- `.env.development`, `.env.production`: 環境變數配置。
- `package.json`: 專案依賴和腳本。
