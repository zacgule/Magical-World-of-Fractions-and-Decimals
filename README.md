# 🍕 基礎數學魔法島：分數與小數互動學習網頁 (Primary 3 Math: Fractions & Decimals)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)]()
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38BDF8?style=flat&logo=tailwind-css&logoColor=white)]()
[![JavaScript ES6+](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=flat&logo=javascript&logoColor=black)]()

專為**香港小學三年級（小三）**學生設計的互動式數學學習網頁。本項目透過直觀的動態視覺化工具與遊戲化教學，協助學生攻克數學課程中「分數」與「小數」兩大核心難關，完全符合香港教育局 (EDB) 數學科課程指引。

An interactive mathematics learning web application designed for Primary 3 (Grade 3) students in Hong Kong. Fully aligned with the Education Bureau (EDB) Mathematics Curriculum Guide, this project helps young learners grasp the core concepts of "Fractions" and "Decimals" through dynamic visual aids and gamified challenges.

[🔗 線上即時體驗 (Live Demo)](#) *https://gemini.google.com/share/9fd514b28f50?skid=e854d19e-930c-4f52-b6f3-a3696ef486ba*

---

## 🚀 項目亮點 (Key Features)

本網頁採用「零依賴 (Zero-Dependency)」與「單網頁應用 (SPA)」設計。無須設定任何開發環境、編譯器或數據庫，直接雙擊網頁即可在任何設備上暢玩！

*   **🍕 第一課：分數概念與同分母比較 (Fractions & Comparisons)**
    *   **動態切披薩工具 (Dynamic Pizza Cutter)：** 利用動態 SVG 技術，讓學生自行調整「分母（總份數）」與「分子（拿取份數）」，實時看見披薩大小變化，直觀理解「等分」概念。
    *   **同分母分數比較 (Fraction Visual Comparison)：** 將抽象的數學大小符號（$<$、$>$、$=$）與兩盤披薩的實體圖形結合，一秒看懂誰多誰少。
*   **🔢 第二課：認識兩位小數與位值 (Decimals & Place Values)**
    *   **100 格百格方塊 (Hundred-Grid Display)：** 學生可以拖動滑桿，自由點亮 1 至 100 格格子，點亮時會實時對應轉換為如 `0.45` 的小數。
    *   **互動數位表 (Dynamic Place Value Chart)：** 清晰劃分「個位」、「小數點」、「十分位」與「百分位」，引導學生理解各數位的位值。
    *   **避坑讀法指南 (Pronunciation Guide)：** 針對小學常考、常犯錯的「兩位小數讀法」進行互動點擊翻牌教學（例如：0.52 必須讀作「零點五二」，而不是「零點五十二」）。
*   **🎮 雙模式遊戲挑戰站 (Gamified Challenges & Reward)**
    *   **遊戲 A (披薩爭奪戰)：** 實時渲染兩盤同分母披薩，挑戰學生點擊正確的比較符號。
    *   **遊戲 B (方塊捕手)：** 根據中文讀法或隨機生成的百格方塊，捕獲正確的小數。
    *   **內置音效與撒花特效：** 採用 Native Web Audio API 合成音效，通關時更會觸發 HTML5 Canvas 滿天飛舞的五彩紙屑（Confetti）慶祝動畫，激發學習成就感！

---

## 🛠️ 技術棧 (Tech Stack)

項目堅持「輕量、高速、純前端」的架構：

*   **HTML5 / CSS3:** 網頁佈局結構，並採用極富童趣的高對比繽紛色彩，適配平板與電腦螢幕。
*   **Tailwind CSS (via CDN):** 現代化響應式 UI 設計與圓角卡片動態效果。
*   **Vanilla JavaScript (ES6+):** 負責所有頁面分頁切換、遊戲狀態管理與 SVG 動態切片算法。
*   **Web Audio API:** 採用瀏覽器原生音頻合成技術調用音波，無需額外下載外部 `.mp3` 音訊檔案。
*   **HTML5 Canvas:** 獨立渲染的彩色流星紙屑慶祝動畫。

---

## 📂 檔案結構 (Project Structure)

本項目完全整合於單一網頁中，極其便於分發和備課使用：

```text
/
├── index.html    # 包含所有 HTML 結構、Tailwind 樣式、和 JS 邏輯的核心單檔案
└── README.md     # 本項目說明文檔（中英雙語）

```

## 💻 快速開始 (Getting Started)
本地運行 (Local Run)
複製此倉庫：

```Bash
git clone [https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git)
cd YOUR_REPO_NAME
```
## 運行項目：

本地無需安裝任何 Node.js 依賴。

雙擊直接打開 index.html 即可在 Chrome, Safari, Edge 或 Firefox 瀏覽器中開始遊玩！

💡 教學推薦： 若是在課堂教學中，可以使用 VS Code 的 Live Server 插件一鍵預覽。

## 部署至 GitHub Pages (Deploy to GitHub Pages)
若要生成線上網址供學生在家或用平板直接掃碼打開：

進入你的 GitHub Repository 設置頁面 (Settings)。

在左側菜單點擊 Pages。

在 Build and deployment 下的 Branch 選擇 main (或 master) 分支並保存。

幾分鐘後，你將獲得一個免費的公共線上網址！

## 📖 香港課程教學目標 (Educational Alignment)
本工具為一線教師與家長而設，旨在達成以下小三數學科課程目標：

分數 (Fractions)：

認識「整體與部分」的關係，並理解「等分」的意思。

認識分子、分母及分數線，並能正確讀寫真分數。

比較同分母分數的大小。

小數 (Decimals)：

藉百格方塊引進兩位小數（百分之一 0.01）。

認識位值，指出小數中各數字的位值（個位、十分位、百分位）。

正確讀、寫及比較兩位小數。

## 🤝 參與貢獻 (Contributing)
這是一個完全開源的教育科技 (EdTech) 項目。我們十分歡迎小學教師、IT 技術人員及 STEM 導師共同完善：

發現 Bug 或文字表述不合適？歡迎提交 Issue。

想增加新的教學模組（例如：分數加減法、小數加法）？歡迎 Fork 項目並提交 Pull Request！

## ⚖️ 授權條款 (License)
本項目採用 MIT 授權條款 開源。你可以自由下載、修改並將其應用於商業教學、校園網課、或家庭教育中。

## 專為香港教育科技、STEM 與數學教育而設。
## Dedicated to promoting EdTech, STEM, and Mathematics Education in Hong Kong.
