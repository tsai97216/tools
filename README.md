---
title: "基地指令：關於本站"
date: 2025-01-01T00:00:00+08:00
draft: false
---

> [!IMPORTANT]
> **此為基於 WebStack-Hugo 的賽博龐克客製化版本。**
> 🛸 [快速進入數據後台 (webstack.yml)](https://github.com/tsai97216/tools/blob/main/exampleSite/data/webstack.yml)
> 🖼️ [快速上傳戰術圖標 (Logos)](https://github.com/tsai97216/tools/upload/main/static/assets/images/logos)

## 關於這個導航站點

這是一個專為效率狂設計的**純靜態響應式導航網頁**。原本是基於 [WebStack-Hugo](https://github.com/shenweiyan/WebStack-Hugo) 開發，但我把它徹底拆解並重新組裝成了更適合台灣特工的版本。

### 為什麼用這個版本？

既然是特工基地，就不該有廢話跟多餘的追蹤。我做了以下改裝：

- **全繁體中文化**：把所有中國用語都洗掉了，這才是我們習慣的介面。
- **切斷外部監控**：拔掉了原本主題裡的百度統計、和風天氣等服務。
- **本土戰術搜尋**：直接整合 Google、YouTube、巴哈姆特，搜東西不用繞路。
- **超輕量天氣系統**：改用 Open-Meteo API，不追蹤位置、讀取超快。
- **全平台適應**：手機、平板或電腦，不管什麼維度看這網站都很美。

### 維護指南

這裡的所有資源都存在 `data/webstack.yml` 檔案裡。如果你想增刪點位，或改裝介面，請參考以下路徑：

- **數據路徑**：`exampleSite/data/webstack.yml`
- **圖標路徑**：`static/assets/images/logos`

**配置範例：**
```yaml
- taxonomy: 常用工具
  icon: fas fa-tools fa-lg
  list:
    - term: 開發工具
      links:
        - title: GitHub
          logo: github.png
          url: [https://github.com/](https://github.com/)
          description: 全球最大的代碼託管平台，代碼改裝倉庫。
