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
| **ðŸŽ›ï¸  Live Configuration Panel** | Securely edit API keys and settings in real-time from the web interface. |

---

## 🔍 Feature Deep Dive

<details>
<summary><b>🗣️ Wake-Word Activation</b></summary>

No buttons, no typing. Just say **"Jarvis"** out loud, and the system wakes up instantly. It activates the Web UI, begins recording your voice input, transcribes it using AI-powered speech recognition, and sends your command to the AI brain — all hands-free. It's the closest thing to having a real J.A.R.V.I.S. on your desktop.

</details>

<details>
<summary><b>🎙️ Voice Control</b></summary>

Jarvis uses real-time speech recognition (via Whisper on Groq or Google's free Speech-to-Text as a fallback) to understand your spoken commands. When he responds, he speaks back to you using **Edge TTS** with a selection of natural, human-like voices. You can even interrupt him mid-sentence by speaking again — he'll stop talking and listen.

</details>

<details>
<summary><b>📱 Telegram Bot</b></summary>

Your personal remote control. Once configured, you can message your Jarvis bot from anywhere in the world — from your phone, tablet, or another computer. Send text commands and get full AI responses back. The bot is **locked to your Telegram user ID**, so nobody else can use it. Jarvis can also proactively message you with reminders, goal nudges, and file transfers.

</details>

<details>
<summary><b>🔄 Proactive Engine</b></summary>

Unlike normal AI assistants that only respond when spoken to, Jarvis has an **autonomous background loop** that runs silently. It loads your personal goals, checks what app you currently have open on screen (Anti-Procrastination Telemetry), reviews your memory, and decides on its own whether to send you a motivational nudge or a reminder via Telegram. It's like having a personal productivity coach watching over your shoulder.

</details>

<details>
<summary><b>🕵️ Silent Web Research</b></summary>

When Jarvis isn't sure about something, he doesn't just guess — he secretly opens a headless browser, performs a web search, scrapes the top results, and reads through them **before** answering you. You never see the search happening; you just get a well-informed, fact-checked response. This runs entirely in the background without cluttering your chat.

</details>

<details>
<summary><b>📝 Web Form Automation</b></summary>

Give Jarvis a Google Form URL (or any web form), tell him what to fill in, and he'll launch a headless Chromium browser via **Playwright**, navigate to the page, intelligently identify form fields, fill them out, and submit — all autonomously. You can even tell him to submit the form multiple times with different data. Perfect for repetitive data entry tasks.

</details>

<details>
<summary><b>👁️ Screen Analysis</b></summary>

Jarvis has **visual awareness** of your physical desktop. If you say "What's on my screen?" or "Look at this error," he will silently take a screenshot of your monitor, encode it, and send it to an AI Vision model (NVIDIA Nemotron or Google Gemini). He then analyzes the image and gives you contextual advice based on exactly what you're looking at — whether it's a code error, a settings page, or a document.

</details>

<details>
<summary><b>📱 Instagram Researcher</b></summary>

Give Jarvis one or more public Instagram handles and a question (e.g., "What kind of content does this person post?"), and he will scrape the profile pages using a headless browser, extract bio info, post captions, and engagement data, and then generate an **analytical report** answering your question. Useful for competitive research, influencer analysis, or simple curiosity.

</details>

<details>
<summary><b>🗂️ App Management</b></summary>

Jarvis can open any application on your Windows PC by name — even if it's buried deep in your Start Menu or registry. He uses a **Smart App Locator** that searches PowerShell's `Get-StartApps`, the Windows Registry, Start Menu `.lnk` files, and your system `PATH`, then uses fuzzy matching to find the best match. He can also close specific apps, or activate a **"Focus Mode"** that kills every application except the ones you whitelist.

</details>

<details>
<summary><b>📁 File System Mastery</b></summary>

Full read/write access to your entire file system. Jarvis can create, read, write, move, and delete files and folders anywhere on your computer. He can also compile text content into **beautifully formatted PDF documents** using themed HTML templates rendered through Chromium. Need a report, a syllabus, or meeting notes turned into a polished PDF? Just ask.

</details>

<details>
<summary><b>⚙️ System Operations</b></summary>

Deep Windows integration via `pywin32` and `ctypes`. Jarvis can:
- 🔒 **Lock your screen** instantly
- 🔊 **Adjust your master volume** to an exact percentage
- 🗑️ **Empty the Recycle Bin** (with confirmation)
- 😴 **Put your PC to sleep**, restart, or shut down
- 💽 **Format disk drives** (with a mandatory safety confirmation gate)

</details>

<details>
<summary><b>🎵 Spotify Integration</b></summary>

Tell Jarvis to play a song, artist, or playlist, and he'll open your **Spotify Desktop app**, launch a headless browser to search Spotify's web player, find the exact track, and trigger playback — all **without needing Spotify API keys**. He can also control media playback: play, pause, skip to the next track, or go back to the previous one using simulated keyboard media keys.

</details>

<details>
<summary><b>📋 Clipboard Access</b></summary>

Jarvis can read whatever text you currently have copied to your clipboard. This means you can copy a block of code, an error message, or a paragraph of text, and then simply say "Jarvis, explain what I just copied" — and he'll read your clipboard and respond with context-aware analysis.

</details>

<details>
<summary><b>⏰ Smart Reminders</b></summary>

Tell Jarvis to remind you about something at a specific time (e.g., "Remind me to call Mom at 6 PM"), and he will schedule a delayed notification. When the time comes, he sends the reminder directly to your phone via **Telegram**. No need for a separate reminders app — your AI handles it.

</details>

<details>
<summary><b>📧 Gmail Integration</b></summary>

Jarvis can connect to your Gmail account using a secure **App Password** (not your main password). He can:
- 📥 **Read your latest unread emails** and summarize them for you
- 📤 **Compose and send emails** on your behalf, including with file attachments
- Supports **multiple Gmail accounts** — just configure a second set of credentials in your `.env` file

</details>

<details>
<summary><b>🛡️ Action Confirmation Gate</b></summary>

Safety first. Jarvis maintains a `DANGEROUS_TOOLS` list that includes actions like formatting drives, permanently deleting files, and emptying the recycle bin. Before executing any of these, the system **intercepts the AI's intent** and forces a manual confirmation popup in the Web UI. This ensures that even if the AI hallucinates or misunderstands a command, it can never accidentally destroy your data without your explicit approval.

</details>

<details>
<summary><b>🧬 Neural Hot-Swapping</b></summary>

Jarvis doesn't depend on a single AI provider. If your primary provider (e.g., Google Gemini) hits a rate limit (HTTP 429), the system **automatically and seamlessly switches** to the next backup provider in your configured chain (e.g., NVIDIA → Mistral → another Gemini key). You can configure up to **5 backup providers** in your `.env` file. When rate limits clear, it swaps back to the primary. You never experience downtime.

</details>

<details>
<summary><b>📅 Google Calendar</b></summary>

After a one-time OAuth setup, Jarvis can check your upcoming calendar events and create new ones — complete with title, start time, duration, description, and attendee invitations. Just say "What's on my calendar today?" or "Schedule a meeting with John at 3 PM tomorrow."

</details>

<details>
<summary><b>📂 Google Drive</b></summary>

Give Jarvis a Google Drive shared link, and he'll download the file (or entire folder) directly to your computer. Useful for quickly grabbing shared documents, datasets, or media files without opening a browser.

</details>

<details>
<summary><b>🧠 Vector Memory (RAG)</b></summary>

Jarvis has **persistent long-term memory** powered by semantic vector embeddings. When you tell him something important (e.g., "My favorite programming language is Python"), he stores it as a vector. Later, when a relevant topic comes up, he performs a **semantic similarity search** to recall the right memories — even if you used different words. This is a full Retrieval-Augmented Generation (RAG) pipeline running locally.

</details>

<details>
<summary><b>🎯 Skills System</b></summary>

Jarvis has an extensible plugin architecture. Skills are simple `.md` or `.txt` files that define new behaviors, personalities, or domain knowledge. You can:
- 📤 **Upload skills** via the Web HUD
- 🔗 **Import skills from a URL**
- 🗑️ **Delete skills** you no longer need

This lets you customize Jarvis's behavior without touching any Python code.

</details>

<details>
<summary><b>🚀 Smart App Locator</b></summary>

The most carefully engineered module in the entire project. It pulls application data from **four different sources**: PowerShell's `Get-StartApps`, the Windows Registry App Paths, Start Menu `.lnk` shortcut files, and the system `PATH` environment variable. It then uses **fuzzy string matching** to find the best match for whatever app name you say — even if you get the name slightly wrong.

</details>

<details>
<summary><b>🧑‍💻 Dedicated Coding Mode</b></summary>

When you ask Jarvis to write complex code, debug a script, or do heavy programming work, he can temporarily **hot-swap his AI brain** from a lightweight model (like Gemini Flash) to NVIDIA's massive **Llama 3.1 70B** model — specifically optimized for code generation. Once the coding task is done, he seamlessly swaps back to the faster model for regular conversation.

</details>

<details>
<summary><b>📺 YouTube Automation</b></summary>

Tell Jarvis to play something on YouTube (e.g., "Play the latest MKBHD video"), and he'll open your default browser and navigate directly to YouTube's search results page with the exact query. Quick and simple — no API keys, no setup.

</details>

<details>
<summary><b>🧹 Show Desktop Panic Button</b></summary>

Jarvis has direct access to the Windows Shell API. With a single command, he can instantly **minimize every open window** on your desktop. Useful for quickly clearing your screen, or as a precursor to taking a clean screenshot for Screen Analysis.

</details>

<details>
<summary><b>📲 PC-to-Phone File Transfer</b></summary>

Because Jarvis is connected to your Telegram bot, he can do more than just send text messages. He can **extract or generate files on your PC** (PDFs, screenshots, documents) and push them directly to your Telegram app on your phone. For example: "Jarvis, generate a syllabus PDF for my biology class and send it to my phone."

</details>

<details>
<summary><b>🎯 Anti-Procrastination Telemetry</b></summary>

The Proactive Engine silently monitors which application window is currently active on your screen using `ctypes` Windows API calls. It feeds this information (e.g., "YouTube - Google Chrome" vs. "Visual Studio Code") into the AI alongside your tracked goals. If it detects you're procrastinating, Jarvis can autonomously send you a **motivational nudge** via Telegram to get you back on track.

</details>

<details>
<summary><b>🧩 Drag-and-Drop Skill Hub</b></summary>

The Web HUD includes a full **skill management center**. You can upload Python skill files directly through the browser, import skills from a URL, view all installed skills, or delete ones you no longer need — all without touching the command line or any config files.

</details>

<details>
<summary><b>🎛️ Live Configuration Panel</b></summary>

The Web HUD includes a **Settings panel** that lets you change your AI provider, API keys, voice, and model in real-time — directly from the browser. Changes are written securely to your `.env` file on disk, and take effect immediately without restarting the server.

</details>

---

## 📁 Directory Structure

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
| `NEMOTRON_API_KEY` | [NVIDIA Build](https://build.nvidia.com/) (Optional — OCR falls back to Gemini if not set) |
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
