# Changelog

所有關於 Portfolio Tracker 的重要更新都將記錄在此文件中。

## [1.1.0] - 2024-03-27

### 新增
- 交易記錄篩選功能
- 價格自動更新提醒

### 改進
- 優化資產管理介面
- 改進價格更新機制
- 提升數據同步效率

### 修復
- 修復資產列表排序問題
- 修復交易記錄顯示異常
- 修復部分 UI 樣式問題

## [1.0.0] - 2024-03-20

### 新增
- 基礎資產管理功能
- 交易記錄追蹤系統
- Google Sheets 數據同步
- 資產價格自動更新
- 基本數據可視化
- 多幣種支持

## [1.2.0] - 2024-03-28

### 改進
- 改進資產和交易記錄的數據處理邏輯
- 優化表頭驗證和錯誤處理機制
- 添加自動初始化表格結構功能
- 改進數值字段的類型轉換處理

### 修復
- 修復 `Cannot read properties of undefined (reading 'toLocaleString')` 錯誤
- 修復 `Cannot read properties of undefined (reading 'toFixed')` 錯誤
- 修復 React 列表渲染中的 "unique key" 問題
- 修復資產 ID 生成和處理邏輯

### 新增
- 添加表頭常量定義（ASSET_HEADERS, TRANSACTION_HEADERS, PRICE_HISTORY_HEADERS）
- 添加詳細的錯誤處理和日誌記錄
- 添加交易類型驗證（買入/賣出）
- 添加數據完整性檢查機制 