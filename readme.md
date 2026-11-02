# ⚙️ MARK LVI (56) — Personal AI Assistant

**The Ultimate Cross-Platform Personal AI Assistant** — Developed by Halim Alimi

A real-time voice AI that can hear, see, speak, and control your computer — on any OS. Supports Windows, macOS, and Linux. Built with modular API and local engine support, delivering total digital autonomy and zero subscription overhead.

---

## ✨ Overview

Mark LV gave the assistant a screen. **Mark LVI lets you choose what runs it.**

Until now this was a Gemini assistant, and only that. If you had no quota left, no connection, or a rule that says your microphone does not leave the building, you had no assistant. Mark LVI adds a second way to hold the conversation — speech recognition, a language model, and a voice, assembled from parts you pick in `⚙ → ENGINE & PROVIDERS` — and a way to point the assistant's own background requests at a different model without touching the voice at all.

The local model can be on your machine (Ollama, LM Studio, llama.cpp, vLLM) or somebody else's API (OpenAI, Groq, DeepSeek, Mistral, xAI, OpenRouter, Together). Both are the same setting, because all of them speak the same protocol.

### 🚀 Key Features

- **Zero Overhead:** On a default install the `providers/` folder is never imported — not at startup, not on a tool call, not when the settings drawer opens. Measured decision time takes 0.16 ms.
- **Full Ecosystem Parity:** A local engine inherits the avatar, the lip-sync, the self-echo guard, push-to-talk, the wake word, memory, undo, the confirmation gate, and every action and plugin.
- **Verified Actions:** Every tool that drives an application answers with what it observed rather than with what it attempted. Done means it was checked; unverified means the request went out and could not be confirmed.
- **Process Watcher:** Opening an app watches the process table for it. Closing one asks the application politely, then checks whether it terminated successfully.

---

## 🛠️ Tech Stack & Requirements

- **Language:** Python 3.10+
- **Core APIs:** Gemini Live API, OpenAI, Groq, DeepSeek, Ollama, and custom endpoints.
- **Dependencies:** Listed in `requirements.txt`.

---

## 📦 Installation & Setup

1. **Clone the repository:**
    ```bash
 git clone https://github.com/halimalimi/jarvis-ai-assistant.git
 cd jarvis-ai-assistant
   '''
2. **Install dependencies:**
   '''bash

   pip install -r requirements.txt
   '''
3. **Run the assistant:**
    '''bash
    python main.py
   '''
## 📄 License

Distributed under the **MIT License**. See `LICENSE` for details.
'''
  
