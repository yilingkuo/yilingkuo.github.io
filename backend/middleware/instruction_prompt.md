# Middleware 目錄指南

## 概述

此目錄用於存放 Express 中間件函數，用於處理請求和響應的通用邏輯。

## 內容

- `authMiddleware.js`: 驗證 JWT token，設置 `req.user`。
- `errorHandler.js`: 全局錯誤處理中間件。
- `logger.js`: 請求日誌記錄。
- `adminMiddleware.js`: 檢查用戶是否為管理員。
