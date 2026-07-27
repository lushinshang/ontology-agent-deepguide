# Ontology Agent Deep Guide

一篇改寫自 Frank Coyle（UC Berkeley）於 AI Engineer 大會演講「[Why Agentic Systems Need Ontologies](https://www.youtube.com/watch?v=Sir59K8ZDPU)」的深度導讀文章，探討為什麼 AI agent 的自主決策錯誤（重複退款、款項發錯人、狀態值失控）沒辦法只靠寫更嚴謹的提示詞解決，以及本體論（ontology）如何以獨立於機率模型的邏輯層，作為 agent 工具呼叫迴圈的驗證關卡。

## 線上閱讀

透過 GitHub Pages 開啟 `index.html` 即可閱讀。

## 內容結構

- 事故案例（重複退款、款項發錯人、狀態值失控）
- 為什麼提示詞救不了機率模型的邏輯漏洞
- 本體論的三個組成部分：型別、關係、限制
- 本體論如何做推論與否決
- agent 工具呼叫迴圈接上本體論驗證器（Pydantic 型別檢查 + reasoner 邏輯檢查）
- 講者介紹與原始影片出處

## 檔案結構

```
.
├── index.html       # 導讀文章主頁面（含內嵌 CSS/JS，開啟即可閱讀）
├── images/          # 資訊圖（每組含 16:9 桌面版與 9:16 手機版）
└── README.md
```

## 圖片生成方式

文中資訊圖由 Codex CLI 的 `image_gen` 工具生成，依段落內容分別繪製：事故案例卡、本體論組成節點圖、agent 迴圈驗證流程圖。

## 出處

- 原始影片：[Why Agentic Systems Need Ontologies — Frank Coyle, UC Berkeley](https://www.youtube.com/watch?v=Sir59K8ZDPU)（AI Engineer）
- 講者：Frank Coyle（[X](https://x.com/coyle_frankp)、[個人網站](https://www.frank-coyle.ai/)）

本文為第三方導讀與詮釋，內容觀點與案例屬原講者原創。
