# Nova Engine
### Sovereign AI — Your Hardware. Your Data. Your AI.

Nova Engine is a local AI assistant that runs entirely on your own Windows PC. No cloud. No subscription. No data ever leaves your machine.

Built by a self-taught barber from St. Catharines, Ontario. 10 months. No CS degree.

---

## What is Nova Engine?

Most AI apps send your conversations to someone else's server. Nova Engine runs the AI on **your own hardware** — your questions, your answers, your memory. Nobody else sees it.

> *"Other AI apps have a 'Do Not Sell My Data' button. Nova Engine doesn't need one."*

---

## Features

- 💬 **AI Chat** — Powered by local LLM (Ollama + Mistral)
- 🔍 **Web Search** — Live search via Firecrawl with Ollama fallback
- 🎨 **Image Generation** — ComfyUI integration
- 📷 **Vision** — Camera and video analysis via LLaVA 13b
- 🧠 **Cross-Session Memory** — ChromaDB persistent memory
- 📱 **Mobile Access** — Android app connects to your PC via Cloudflare Tunnel
- 🔒 **100% Local** — No cloud dependency, no API keys required to run

---

## How It Works

Nova Engine has two components:

1. **Windows Backend** — Flask server running on your PC with Ollama, ComfyUI, and ChromaDB
2. **Android App** — Available on Google Play, connects to your PC via your personal Cloudflare tunnel URL

Your phone talks to your PC. Your PC does the AI. Nothing goes anywhere else.

---

## Download

### Windows Installer
[⬇️ Download NovaEngine_Setup_v1.5.exe](https://github.com/NovaEngineLabs/nova-engine/releases/latest)

**Requirements:**
- Windows 10/11 64-bit
- 8GB RAM minimum
- GPU recommended (NVIDIA for best performance)
- ~15GB free disk space (includes Ollama + model)

### Android App
[📱 Get it on Google Play](https://play.google.com/store/apps/details?id=com.novaengine.app)

---

## Setup

1. Download and run the Windows installer
2. Follow the setup wizard — it installs Ollama, pulls your LLM, and configures your Cloudflare tunnel
3. Enter your Cloudflare tunnel URL into the Android app
4. Your phone is now connected to your own sovereign AI

---

## Tech Stack

| Component | Technology |
|---|---|
| Backend | Python, Flask |
| LLM | Ollama (Mistral, phi3) |
| Image Gen | ComfyUI |
| Vision | LLaVA 13b |
| Memory | ChromaDB, SQLite |
| Tunnel | Cloudflare Tunnel |
| Android | Kotlin, WebView |
| Installer | Inno Setup |

---

## License

Nova Engine Software License — Copyright © 2026 Nova Engine Labs

Personal, non-commercial use only. Redistribution, resale, or commercial use without explicit written permission from Nova Engine Labs is strictly prohibited.

Contact: novaenginelabs@gmail.com

---

## Links

- 🌐 [novaenginelabs.com](https://novaenginelabs.com)
- 📱 [Google Play](https://play.google.com/store/apps/details?id=com.novaengine.app)
- 📧 [novaenginelabs@gmail.com](mailto:novaenginelabs@gmail.com)
