# Stores 目錄指南 (Pinia)

## 概述

此目錄用於存放 Pinia 狀態管理模組，用於管理應用程式的全局狀態。

## 內容

- 每個檔案代表一個 Pinia Store (例如 `auth.js`, `recipes.js`, `techNotes.js`, `cart.js`)。

## 狀態管理

- 定義狀態 (state)、獲取器 (getters)、動作 (actions)。
- 處理非同步操作 (如 API 呼叫) 在 actions 中。
