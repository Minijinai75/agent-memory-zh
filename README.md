# Agent 記憶架構（繁中）

《Agent Memory Architecture — 5 Layers That Cut Token Cost 90%》的台灣繁體中文靜態譯本。原文為 2026 年獨立整理的工程筆記（綜合 CoALA、Mem0、Anthropic memory、Snowflake ontology、LangChain 等公開材料），**非 Anthropic 官方文件**。

預期線上網址：

**https://minijinai75.github.io/agent-memory-zh/**

網站檔案在 `main` 根目錄的 `index.html`。`.github/workflows/pages.yml` 會用官方 GitHub Actions 部署靜態檔。此 repo 的自動化權杖沒有 `pages:write`／admin，無法用 API 直接打開 Pages；請 repo 擁有者做一次：

1. 打開 [Settings → Pages](https://github.com/Minijinai75/agent-memory-zh/settings/pages)
2. Build and deployment → Source 選 **GitHub Actions**
3. 到 [Actions](https://github.com/Minijinai75/agent-memory-zh/actions) 重跑 **Deploy GitHub Pages**，或再 push 一次 `main`

啟用後網站會出現在上述 github.io 網址。

本機預覽：用瀏覽器直接開啟 `index.html`，或在 repo 根目錄執行：

```bash
python3 -m http.server 8080
```

然後造訪 `http://localhost:8080/`。

## 內容涵蓋

問題陳述、五層記憶（工作／情節／語意／程序／遺忘）、實證與反模式、一週建置路徑、決策框架、上線檢查清單、多 Agent、進階模式、各領域設定、測試、結論、詞彙表與參考文獻。程式碼清單維持英文。
