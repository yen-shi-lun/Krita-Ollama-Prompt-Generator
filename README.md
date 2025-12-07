Wuhe Design – Krita × Ollama Prompt Generator
Local LLM Prompt Generator for Krita (Gemma / Ollama / AI Diffusion Integration)
Overview｜插件介紹

English
The Krita × Ollama Prompt Generator by Wuhe Design is a local-LLM powered plugin that allows artists and designers to generate, refine, translate, and send prompts directly inside Krita — without relying on cloud APIs.
It fully integrates with krita-ai-diffusion (Stable Diffusion plugin), enabling one-click prompt transfer to the diffusion prompt box.

繁體中文
Wuhe Design 推出的 Krita × Ollama Prompt Generator 是一款在 Krita 內即可使用的本地 LLM 提示詞生成插件。
支援 Gemma 等多種 Ollama 模型，可自動生成提示詞、雙語輸出、語音輸入，並能直接把提示詞送到 krita-ai-diffusion 的生成框內，全流程在你的電腦本機完成，不需 API、不中斷、不跳視窗。

✨ Features｜主要功能
English
🔍 Auto-detects all local Ollama models (e.g., gemma3:4b, gemma3:27b)
🧠 One-click prompt generation & refinement
🎙️ Built-in voice input
🌐 Bilingual output: English + Chinese
🔄 Send prompt directly to krita-ai-diffusion
♻️ Reset LLM context anytime
🖥️ Fully integrated UI inside Krita (dockable panel)

繁體中文
🔍 自動偵測本地 Ollama 模型（gemma3:4b、27b…）
🧠 一鍵生成／優化提示詞
🎙️ 內建語音輸入
🌐 雙語輸出（英文／中文）
🔄 一鍵傳送到 krita-ai-diffusion 的提示詞框
♻️ 重置模型對話 Context
🖥️ 完整整合於 Krita 介面，可自由停靠

🔗 Integration with krita-ai-diffusion｜與 Stable Diffusion 外掛連動
English
This plugin integrates directly with
👉 Acly/krita-ai-diffusion
You can generate a prompt → click Send to AI Plugin → and the text will be inserted into the Stable Diffusion prompt box automatically.

繁體中文
插件已完整整合：
👉 Acly/krita-ai-diffusion（Stable Diffusion 外掛）
按下：
「Send English to AI Plugin」 或 「Send Chinese to AI Plugin」
提示詞會自動填入 Stable Diffusion 的生成框。

📦 Installation｜安裝方式
1. Download
（你之後可放 release 下載連結）
2. Extract into Krita plug-in folder
Windows:
%APPDATA%\krita\pykrita\
macOS:
/Users/<YOUR_NAME>/Library/Application Support/krita/pykrita/
Linux:
~/.local/share/krita/pykrita/
3. Enable Plugin
Krita → 工具 Tools → Python 外掛管理
啟用：
Ollama Prompt Generator
4. Restart Krita
🖥️ Screenshots｜使用畫面

（你之後可以自己補上圖片）

⚙️ Requirements｜系統需求
Krita 5.2+
Ollama installed
Any Gemma model (4B / 27B recommended)
Windows / macOS / Linux

🧩 Folder Structure｜外掛結構
pykrita/
 └── OllamaPromptGenerator/
      ├── __init__.py
      ├── plugin.desktop
      ├── main.py
      ├── ui/
      ├── icons/
      └── README.md

❤️ About Wuhe Design｜關於吾禾設計

English
Wuhe Design focuses on AI × Architecture, AI × Interior Design, and practical creative tools.
Our mission: build AI tools that designers can truly use.

繁體中文
吾禾設計致力於 AI × 建築、AI × 室內設計與實用工具開發，
打造真正落地的 AI 創作工具，改善每位設計師的工作流程。

🤝 Contribute｜參與開發
Pull Requests and Issues are welcome!
📜 License｜授權
MIT License
