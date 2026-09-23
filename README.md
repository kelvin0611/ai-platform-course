# AI 學習平台 · 5 堂課程（課程網站）

> 中六 · 10 小時 · 唔需要識寫程式

## 👉 學生入口

**https://kelvin0611.github.io/ai-platform-course/**

用電話開都得。每一堂有齊：**先明白（兩三句）→ 步驟（細步）→ 可以複製嘅 Prompt**。

## 配套 repo

| | |
|---|---|
| **呢個 repo** | 逐堂步驟（rundown）|
| **[ai-platform-prompts](https://github.com/kelvin0611/ai-platform-prompts)** | Prompt 表格（一鍵複製）＋ **起手檔** |

學生實際會開兩個網站：

- 上課跟步驟 → 呢個
- 做嘢實際 copy prompt → [Prompt 表格](https://kelvin0611.github.io/ai-platform-prompts/)

## 五堂一覽

| 堂 | 主題 | 做完之後 |
|---|---|---|
| 1 | 出第一件作品 | 一個虛擬實驗，放上導師平台，有條真 link |
| 2 | 你個平台出世 | 平台名／科目／配色變成你嘅 ＋ 加「最近更新」|
| 3 | 放你自己嘅內容入去 | 筆記 ＋ 自己堂 1 造嘅虛擬實驗 |
| 4 | 加你自己揀嘅功能 | 自選功能用得，原本嘢冇壞 |
| 5 | 出街 | 公開 link ＋ QR code ＋ 3 分鐘 demo |

## 設計原則

**每堂都有兩段，唔可以跳。**

| | |
|---|---|
| 🟦 **先明白** | 用 Prompt 叫 AI 解釋，唔係叫佢做嘢 |
| 🟩 **後動手** | 明白之後才叫佢做 |

**每一步都有「你會見到」** —— 對唔上就係出咗事。呢個就係驗收訓練。

**骨架預先做好**（見 ai-platform-prompts 嘅 template）——
學生唔需要捱白畫面，佢哋專注學「提出需求」同「寫 Prompt」。

## 三句口頭禪

> 1. **「你要嘅係咩？用一句話講出嚟，先撳 Enter。」**
> 2. **「跑一次，睇住個畫面。」**
> 3. **「AI 話做好咗，唔等於做好咗。」**

## 維護（導師用）

課程內容全部喺 `index.html`，用 `<section data-lesson="N">` 分堂。
每步係一個 `<div class="step">`，入面嘅 `<pre class="prompt">` 就係學生複製嘅嘢。

改完直接 push，GitHub Pages 一分鐘內更新。

> ⚠️ Prompt 嘅 id 要同 `<button class="copy" data-target="...">` 對得上，唔係個掣會複製唔到嘢。
