<div align="center">

# ðŸ§  Nexus VII â€” Autonomous Intelligence

**A J.A.R.V.I.S.-inspired autonomous AI assistant with voice control, Telegram integration, proactive reminders, web form automation, screen analysis, and neural hot-swapping across multiple AI providers.**

Built with Python Â· FastAPI Â· WebSockets

<br>
<img src="https://img.shields.io/github/license/saruk-vedant/Nexus-VII-Autonomous-Intelligence?style=flat-square" alt="License">
<img src="https://img.shields.io/github/stars/saruk-vedant/Nexus-VII-Autonomous-Intelligence?style=flat-square" alt="Stars">
<img src="https://img.shields.io/github/forks/saruk-vedant/Nexus-VII-Autonomous-Intelligence?style=flat-square" alt="Forks">
<img src="https://img.shields.io/github/issues/saruk-vedant/Nexus-VII-Autonomous-Intelligence?style=flat-square" alt="Issues">
<br>

</div>

---

## âœ¨ Features

| Feature | Description |
|---------|-------------|
| **ðŸ—£ï¸ Wake-Word Activation** | Hands-free experience. Just say "Jarvis" to wake the system, activate the Web UI, and start recording your input. |
| **ðŸŽ™ï¸ Voice Control** | Speak to your assistant using real-time speech recognition and human-like TTS responses. |
| **ðŸ“± Telegram Bot** | Remote control and notifications via a personal Telegram bot. |
| **ðŸ”„ Proactive Engine** | Autonomous background AI that monitors your goals and sends nudges. |
| **ðŸ•µï¸ Silent Web Research** | Background web searches to fact-check or gather context before responding, without clogging the chat. |
| **ðŸ“ Web Form Automation** | AI-powered Google Forms and web form filling via Playwright. |
| **ðŸ‘ï¸ Screen Analysis** | Visual awareness of your desktop. Ask "Look at my screen" to take a screenshot and get contextual advice. |
| **ðŸ“± Instagram Researcher** | Built-in ability to scrape public Instagram profiles and generate analytical reports on them. |
| **ðŸ—‚ï¸ App Management** | Open and close specific applications, or execute a "focus mode" by closing all non-essential apps. |
| **ðŸ“ File System Mastery** | Read, write, move, delete, and create files/folders anywhere. Compile text into formatted PDFs. |
| **âš™ï¸ System Operations** | Lock screen, adjust master volume, empty recycle bin, put PC to sleep, restart, or format drives. |
| **ðŸŽµ Spotify Integration** | Search for and play specific songs, artists, or playlists on Spotify desktop, and control media playback. |
| **ðŸ“‹ Clipboard Access** | Read whatever text you currently have copied to your clipboard. |
| **â° Smart Reminders** | Schedule delayed pings to your phone by setting a reminder at a specific time. |
| **ðŸ“§ Gmail Integration** | Read your latest unread emails and compose/send new emails on your behalf. |
| **ðŸ›¡ï¸ Action Confirmation Gate** | Intercepts highly destructive actions (like formatting a drive) and forces a manual prompt for safety. |
| **ðŸ§¬ Neural Hot-Swapping** | Seamless automatic failover across multiple AI providers when rate limits hit. |
| **ðŸ“… Google Calendar** | Check and create calendar events via the Google Calendar API. |
| **ðŸ“‚ Google Drive** | Download files and entire folders from Google Drive shared links. |
| **ðŸ§  Vector Memory** | Persistent long-term memory with semantic recall (RAG). |
| **ðŸŽ¯ Skills System** | Extensible skill/plugin system to teach your AI new behaviors. |
| **ðŸš€ Smart App Locator** | Dynamically finds and launches Windows apps using deep registry scanning. |
| **ðŸ§‘â€ðŸ’» Dedicated Coding Mode** | Hot-swaps to NVIDIA's massive Llama 3.1 70B model specifically for complex coding tasks. |
| **ðŸ“º YouTube Automation** | Autonomously opens your browser and runs specific YouTube search queries. |
| **ðŸ§¹ Show Desktop Panic Button** | Instantly minimize every single window on your computer using Windows shell APIs. |
| **ðŸ“² PC-to-Phone File Transfer** | Generates or extracts files from your PC and sends them directly to your Telegram app. |
| **ðŸŽ¯ Anti-Procrastination Telemetry** | Silently checks the active screen window to send context-aware nudges if you are distracted. |
| **ðŸ§© Drag-and-Drop Skill Hub** | Install new capabilities by dropping Python scripts or URLs directly into the Web HUD. |
| **ðŸŽ›ï¸ Live Configuration Panel** | Securely edit API keys and settings in real-time from the web interface. |

---

## ðŸ“ Directory Structure

```
Nexus-VII-Autonomous-Intelligence/
â”œâ”€â”€ api/             # External service integrations (Telegram bot, reminders)
â”œâ”€â”€ auth/            # Google OAuth credentials (you provide these)
â”œâ”€â”€ core/            # Main AI engine, server, vector memory, proactive engine
â”œâ”€â”€ data/            # Local databases, caches, memory, and goals
â”œâ”€â”€ docs/            # Project documentation and ideas
â”œâ”€â”€ modules/         # Specialized modules (OCR, Calendar, Drive, PDF, App Locator)
â”œâ”€â”€ scripts/         # Utility scripts (Syllabus generator, file organizer)
â”œâ”€â”€ skills/          # AI behavior rules and skill files (.md/.txt)
â”œâ”€â”€ static/          # Web UI (HTML, CSS, JS, particles)
â”œâ”€â”€ temp/            # Temporary processing files
â”œâ”€â”€ tests/           # Test scripts
â”œâ”€â”€ .env.example     # Environment variable template (copy to .env)
â”œâ”€â”€ launch_jarvis.bat# One-click launcher for Windows
â””â”€â”€ requirements.txt # Python dependencies
```

---

## ðŸš€ Quick Start (Step-by-Step)

Follow these steps exactly and you will have Nexus VII running in under 5 minutes.

### Prerequisites

- **Python 3.10+** â†’ [Download here](https://www.python.org/downloads/) âš ï¸ **Check "Add Python to PATH"** during installation!
- **Windows 10/11** â†’ This project uses Windows-specific APIs (registry, PowerShell, etc.)
- **Git** â†’ [Download here](https://git-scm.com/)
- **Spotify Desktop** â†’ (Optional) Required for Spotify automation (must be installed and logged in)

### Step 1: Clone the Repository

```bash
git clone https://github.com/saruk-vedant/Nexus-VII-Autonomous-Intelligence.git
cd Nexus-VII-Autonomous-Intelligence
```

### Step 2: Create & Activate a Virtual Environment

```bash
python -m venv venv
venv\Scripts\activate
```

> âš ï¸ If `python` is not recognized, try `py` instead of `python`.

### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

This will install all required packages. It may take 2â€“5 minutes on the first run.

### Step 4: Install Playwright Browsers

```bash
playwright install
```

This downloads the headless Chromium browser needed for web automation and PDF generation.

### Step 5: (Optional) Install Tesseract OCR

If you want the OCR / screen-reading feature:
- Download the installer from [UB-Mannheim/tesseract](https://github.com/UB-Mannheim/tesseract/wiki)
- Run the installer with default settings
- Tesseract will be auto-detected

### Step 6: Configure Your API Keys

```bash
copy .env.example .env
```

Open the `.env` file in any text editor (Notepad, VS Code, etc.) and fill in your API keys:

#### ðŸ”‘ Required (at minimum one AI key)

| Variable | Where to Get It |
|----------|----------------|
| `AI_API_KEY` | [Google AI Studio](https://aistudio.google.com/) â€” **free** |
| `AI_BASE_URL` | Pre-filled for Gemini. Change if using Groq/Ollama. |
| `AI_MODEL` | Pre-filled. Change if using a different model. |

#### ðŸ”Œ Optional Integrations

| Variable | Where to Get It |
|----------|----------------|
| `GEMINI_API_KEY` | Same as above, used for vision & memory features |
| `NVIDIA_API_KEY` | [NVIDIA Build](https://build.nvidia.com/) |
| `NEMOTRON_API_KEY` | [NVIDIA Build](https://build.nvidia.com/) (Required for OCR / Screen Analysis) |
| `BACKUP_*` keys | Additional API keys for hot-swap failover |
| `GMAIL_ADDRESS` | Your Gmail address |
| `GMAIL_APP_PASSWORD` | [Google App Passwords](https://myaccount.google.com/apppasswords) (requires 2FA) |
| `TELEGRAM_BOT_TOKEN` | Create a bot via [@BotFather](https://t.me/BotFather) on Telegram |
| `TELEGRAM_ALLOWED_UID` | Get your ID via [@userinfobot](https://t.me/userinfobot) on Telegram |

### Step 7: Set Up Google Calendar & Drive (Optional)

To enable Google Calendar and Drive features:

1. Go to the [Google Cloud Console](https://console.cloud.google.com/).
2. Create a new project (or select an existing one).
3. Enable the **Google Calendar API** and **Google Drive API**.
4. Go to **Credentials** â†’ **Create Credentials** â†’ **OAuth 2.0 Client ID**.
5. Download the JSON file and save it as `auth/credentials.json`.
6. On first use, a browser window will open for you to authorize access. The resulting `auth/token.json` will be created automatically.

### Step 8: Launch! ðŸš€

**Option A: One-click (recommended)**
```bash
launch_jarvis.bat
```

**Option B: Manual**
```bash
venv\Scripts\activate
python core/server.py
```

Then open **http://localhost:8000** in your browser. You're in! ðŸŽ‰

---

## ðŸ–¥ï¸ Web UI

The HUD (Heads-Up Display) runs in your browser and provides:

- Real-time chat with the AI (text + voice)
- System telemetry (CPU, RAM, power, storage)
- Memory management (add/view/edit persistent memories)
- Settings panel (change AI provider, keys, voice, integrations)
- Skills center (import, upload, and manage AI skills)
- File upload and image analysis

---

## ðŸ¤– Telegram Setup

1. Open Telegram and message [@BotFather](https://t.me/BotFather).
2. Send `/newbot` and follow the prompts to create your bot.
3. Copy the bot token and paste it into `TELEGRAM_BOT_TOKEN` in your `.env`.
4. Message [@userinfobot](https://t.me/userinfobot) to get your Telegram user ID.
5. Paste your ID into `TELEGRAM_ALLOWED_UID` in your `.env`.
6. Restart the server. Your bot will now be active!

---

## ðŸ§¬ Supported AI Providers

| Provider | Base URL | Models |
|----------|----------|--------|
| **Google Gemini** | `https://generativelanguage.googleapis.com/v1beta/openai/` | `gemini-3.5-flash-lite`, `gemini-3.5-flash` |
| **NVIDIA** | `https://integrate.api.nvidia.com/v1` | `meta/llama-3.3-70b-instruct`, `nvidia/nemotron-3-super-120b-a12b` |
| **Mistral AI** | `https://api.mistral.ai/v1` | `mistral-small-latest` |
| **Groq** | `https://api.groq.com/openai/v1` | `llama-3.1-8b-instant` |
| **Ollama** (local) | `http://localhost:11434/v1` | Any locally running model |

The neural hot-swapping system automatically rotates through your configured backup providers when rate limits are encountered.

---

## ðŸ“œ Scripts

Utility scripts in the `scripts/` folder:

| Script | Description |
|--------|-------------|
| `generate_syllabus.py` | Generates a beautifully formatted PDF syllabus from course data. |
| `organize_files.py` | Organizes files in a folder by name-based numeric sorting. |

---

## ðŸ”’ Security Notes

- Your `.env` file is **gitignored** and will never be committed.
- `auth/credentials.json` and `auth/token.json` are **gitignored**.
- Personal data files (`memory_db.json`, `goals.json`, `memory.txt`, `app_cache.json`) are **gitignored**.
- The Telegram bot only responds to the user ID specified in `TELEGRAM_ALLOWED_UID`.

---

## â“ Troubleshooting

| Problem | Solution |
|---------|----------|
| `python is not recognized` | Use `py` instead of `python`, or reinstall Python with "Add to PATH" checked. |
| `pip install` fails with encoding errors | Make sure you downloaded the latest version of this project. The `requirements.txt` must be UTF-8 encoded. |
| `playwright install` hangs or fails | Run your terminal as Administrator and try again. |
| Server crashes on startup | Make sure you copied `.env.example` to `.env` and filled in at least `AI_API_KEY`. |
| Telegram bot not working | Ensure `TELEGRAM_BOT_TOKEN` and `TELEGRAM_ALLOWED_UID` are correctly set in `.env`. |

---

## ðŸ“ License

Distributed under the MIT License. See `LICENSE` for more information.

---

## ðŸ™ Acknowledgments

Inspired by J.A.R.V.I.S. from the Marvel Cinematic Universe.
Built with Python, FastAPI, and Playwright.
