<p align="center"> <a href="#english-version--english-readme"> <img src="https://img.shields.io/badge/Language-English-blue?style=for-the-badge" /> </a> &nbsp; <a href="#繁體中文版本--traditional-chinese-readme"> <img src="https://img.shields.io/badge/語言-繁體中文-red?style=for-the-badge" /> </a> </p>
<a id="english-version--english-readme"></a>🇺🇸 English Version | English README
🖌️ Wuhe Design – Krita × Ollama Prompt Generator
Local LLM Prompt Generator for Krita (Gemma / Ollama / AI Diffusion Integration)
🎨 Overview

The Krita × Ollama Prompt Generator by Wuhe Design is a local-LLM powered plugin that allows artists and designers to generate, refine, translate, and send prompts directly inside Krita — without relying on cloud APIs.
It fully integrates with krita-ai-diffusion, enabling one-click prompt transfer to the Stable Diffusion prompt box.

✨ Features
🔍 Auto-detects all local Ollama models (e.g., gemma3:4b, gemma3:27b)
🧠 One-click prompt generation and refinement
🎙️ Built-in voice input
🌐 Bilingual output (English / Chinese)
🔄 Send prompts directly to krita-ai-diffusion
♻️ Reset LLM conversation context
🖥️ Dockable UI panel integrated inside Krita
🔗 Integration with krita-ai-diffusion

This plugin integrates directly with
👉 Acly/krita-ai-diffusion

Generate prompts using a local LLM → click Send to AI Plugin → the text is instantly inserted into the Stable Diffusion prompt input.

No copy-paste.
No window switching.
Fully inside Krita.

📦 Installation
1. Download
(Release link can be added here later)

2. Extract into Krita plugin folder:
Windows:
%APPDATA%\krita\pykrita\

macOS:
/Users/<YOUR_NAME>/Library/Application Support/krita/pykrita/

Linux:
~/.local/share/krita/pykrita/

3. Enable Plugin
Krita → Tools → Manage Python Plugins
Enable: Ollama Prompt Generator

4. Restart Krita
🖼️ Screenshots
(You may upload images here later)

⚙️ Requirements
Krita 5.2+
Ollama installed
Any Gemma model (4B / 27B recommended)
Windows / macOS / Linux

🧩 Folder Structure
pykrita/
 └── OllamaPromptGenerator/
      ├── __init__.py
      ├── plugin.desktop
      ├── main.py
      ├── ui/
      ├── icons/
      └── README.md

❤️ About Wuhe Design
Wuhe Design focuses on AI × Architecture, AI × Interior Design, and practical creative tools that enhance real workflows.
Our mission is to build AI tools that designers can truly use.

🤝 Contribute
Pull Requests and Issues are welcome.

📜 License
MIT License

<a id="繁體中文版本--traditional-chinese-readme"></a>🇹🇼 繁體中文版本 | Traditional Chinese README
🖌️ 吾禾設計 – Krita × Ollama Prompt Generator
在 Krita 中使用本地 LLM（Gemma / Ollama）生成提示詞的 AI 插件
🎨 插件介紹

Krita × Ollama Prompt Generator 是由吾禾設計開發的本地 LLM 提示詞生成外掛。
所有處理皆在你的電腦中執行，不需 API、不需雲端，同時支援多種 Gemma 模型，可用於：
生成提示詞
優化重寫提示詞
英文／中文雙語輸出
語音輸入
一鍵傳送到 krita-ai-diffusion
整個流程不跳視窗、不複製貼上，全在 Krita 裡完成。

✨ 主要功能
🔍 自動偵測本地 Ollama 模型（gemma3:4b、27b…）
🧠 一鍵生成與優化提示詞
🎙️ 內建語音輸入
🌐 雙語輸出（英文／中文）
🔄 一鍵傳送至 krita-ai-diffusion 提示詞框
♻️ 重置模型對話 Context
🖥️ UI 介面完整整合於 Krita，可自由停靠
🔗 與 krita-ai-diffusion 整合

外掛可直接與
👉 Acly/krita-ai-diffusion（Stable Diffusion 外掛）
連動。

按下：
Send English to AI Plugin
Send Chinese to AI Plugin
提示詞會直接填入 Stable Diffusion 的生成框。
無需複製貼上、不切視窗、不中斷繪圖流程。

📦 安裝方式
1. 下載
（之後可加入 release 連結）
2. 將外掛解壓到以下路徑：
Windows:
%APPDATA%\krita\pykrita\

macOS:
/Users/<YOUR_NAME>/Library/Application Support/krita/pykrita/

Linux:
~/.local/share/krita/pykrita/

3. 啟用外掛
Krita → Tools → Python 外掛管理
勾選：Ollama Prompt Generator

4. 重啟 Krita
🖼️ 使用畫面
（你可日後補上）

⚙️ 系統需求
Krita 5.2+
已安裝 Ollama
建議使用 Gemma 模型（4B / 27B）
Windows / macOS / Linux

🧩 外掛結構
pykrita/
 └── OllamaPromptGenerator/
      ├── __init__.py
      ├── plugin.desktop
      ├── main.py
      ├── ui/
      ├── icons/
      └── README.md

❤️ 關於吾禾設計
吾禾設計專注於：
AI × 建築
AI × 室內設計
設計師的 AI 工具落地應用
目標是打造每位設計師真正用得上的 AI 工具。
🤝 參與開發
歡迎提交 Issues、Pull Requests。
📜 授權
MIT 授權
