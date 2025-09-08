# AI Voice Agent

**AI Voice Agent** is a Python 3.10+ project that combines **LiveKit Agents** with **Google Realtime API** to enable real-time voice and video conversations. It supports noise cancellation, customizable instructions, and secure environment-based configuration.

---

## Features

* Real-time AI conversations using Google’s Realtime LLM
* Noise cancellation via **LiveKit BVC plugin**
* Customizable agent instructions (`prompts.py`)
* Secure environment variable handling using **dotenv**
* Easy-to-run CLI commands: `download-files`, `console`, `dev`

---

## Tech Stack

* **Language:** Python 3.10+
* **SDK:** LiveKit Agents
* **API:** Google Realtime API
* **Environment Management:** dotenv
* **Concurrency:** asyncio
* **Noise Cancellation Plugin:** LiveKit BVC

---

## Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/yourusername/ai-voice-agent.git
cd ai-voice-agent
```

Create and activate a virtual environment:

```bash
python -m venv venv
.\env\Scripts\activate
```

Upgrade pip and install requirements:

```bash
python -m pip install --upgrade pip setuptools wheel
python -m pip install -r requirements.txt
```

---

## Environment Variables

Create a `.env` file in the project root:

```bash
LIVEKIT_URL=your_livekit_url
LIVEKIT_API_KEY=your_livekit_api_key
LIVEKIT_API_SECRET=your_livekit_api_secret
GOOGLE_API_KEY=your_google_api_key
GMAIL_APP_PASSWORD=your_gmail_app_password
GMAIL_USER=your_gmail_address
```
---

## Available Scripts

```bash
python agent.py download-files   # Download required assets
python agent.py console          # Start interactive console mode
python agent.py dev           # Run in development mode
```
