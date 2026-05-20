<div align="center">

# **Hydrix AI NPC** 
**Advanced Local AI Conversations for FiveM**

![FiveM](https://img.shields.io/badge/FiveM-Server-blue?style=for-the-badge)
![QBox](https://img.shields.io/badge/QBox-Core-purple?style=for-the-badge)
![Ollama](https://img.shields.io/badge/Ollama-Local%20AI-green?style=for-the-badge)
![ox_target](https://img.shields.io/badge/ox_target-Enabled-orange?style=for-the-badge)

**Next-Gen AI NPCs powered by local LLMs**

</div>

---

## ✨ Features

- **Local AI** — Fully offline using **Ollama**
- **ox_target** integration — Clean NPC interaction
- **Dynamic Conversations** — Each NPC has unique personality
- **QBox + ox_lib** compatible
- **Emotion Reactions** — NPCs react with animations
- **Speech Bubble** — Floating text above NPC
- **Configurable** — Easy to add new NPCs and personalities

---

## 📸 Preview

*(Add screenshots/GIFs here later)*

---

## 🚀 Installation

1. **Download Ollama**
   - Go to [ollama.com](https://ollama.com) and install it

2. **Pull a Model**
   ```bash
   ollama pull llama3.2

Download the ResourceBashgit clone https://github.com/YOURNAME/hydrix_ainpc.git
Move the folder to your resources/ directory and rename it to hydrix_ainpc
Add to server.cfgcfgensure hydrix_ainpc


⚙️ Configuration
Make sure your config.lua has the correct Ollama settings:
LuaConfig.LLMEndpoint = 'http://localhost:11434/v1/chat/completions'
Config.LLMModel = 'llama3.2'        -- Must match `ollama list`
Check your model name with:
Bashollama list

🎮 How To Use

Talk to NPCs → Walk up and press E (or use ox_target)
Voice Mode (WIP) → Press N near an NPC
Admin Command: /ainpc forget — Clears conversation memory


🛠️ Current Status

✅ Text Chat with AI
✅ ox_target + Streaming NPCs
✅ Local LLM (Ollama)
✅ Emotion + Animation system
🔄 TTS (Text-to-Speech) — In Progress
🔄 Full Voice Input (Speech-to-Text) — Planned


🤝 Contributing
This is an Alpha version. Feel free to fork it and contribute!
Want to help? Message me or open a Pull Request.

⭐ Credits

Built with ❤️ by Hydrix //
Powered by Ollama //
UI & Target by ox_lib / ox_target
