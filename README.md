---
title: "關於本站"
date: 2025-01-01T00:00:00+08:00
draft: false
---

> [!NOTE]
> **此為基於 WebStack-Hugo 的客製化繁體中文版本。**

## 一個基於 Hugo 的靜態響應式網址導航主題

本專案是基於**純靜態**的網址導航網站 [webstack.cc](https://github.com/WebStackPage/WebStackPage.github.io) 製作的 [Hugo](https://gohugo.io/) 主題，是一個基於 Hugo 的靜態響應式網址導航主題。<br/>

### 主題開源地址（原作者）

[**GitHub**](https://github.com/shenweiyan/WebStack-Hugo) | [**Gitee**](https://gitee.com/shenweiyan/WebStack-Hugo)

### 特色功能

這是 Hugo 版 WebStack 主題。可以借助下面的平台直接託管部署，無需伺服器。
- [Cloudflare Pages](https://pages.cloudflare.com) | [Vercel](https://vercel.com) | [Github Pages](https://pages.github.com/) | [Netlify](https://app.netlify.com/)

**本站客製化特點：**

- **完全繁體中文化**：介面與用語皆調整為台灣習慣用法。
- **去中國化依賴**：移除了百度統計、百度搜尋 API、和風天氣等中國服務。
- **本地化搜尋**：整合 Google 搜尋、YouTube、維基百科、巴哈姆特等台灣常用服務。
- **極簡天氣與語錄**：改用 Open-Meteo 免費天氣 API 與本地隨機語錄腳本，速度更快且無追蹤。
- **自適應設計**：完美支援手機、平板與電腦，並支援自動/手動夜間模式。
- **配置簡單**：主要的配置資訊都整合到了 `config.toml`，導航資訊整合在 `data/webstack.yml` 文件中，方便後續增刪改動。

**配置範例 (`data/webstack.yml`)：**
```yaml
- taxonomy: 常用工具
  icon: fas fa-tools fa-lg
  list:
    - term: 開發工具
      links:
        - title: GitHub
          logo: github.png
          url: [https://github.com/](https://github.com/)
          description: 全球最大的代碼託管平台。
        - title: ChatGPT
          logo: openai.png
          url: [https://chat.openai.com/](https://chat.openai.com/)
          description: OpenAI 人工智慧聊天機器人。
    - term: 雲端服務
      links:
        - title: Google Cloud
          logo: gcp.png
          url: [https://cloud.google.com/](https://cloud.google.com/)
          description: Google 雲端平台。
        - title: AWS
          logo: aws.png
          url: [https://aws.amazon.com/tw/](https://aws.amazon.com/tw/)
          description: Amazon Web Services。
