AI Voice Agent

AI Voice Agent is a Python 3.10 project that combines LiveKit Agents with Google Realtime API to enable real-time voice and video conversations. It supports noise cancellation, custom instructions, and secure environment-based configuration.

Features

Real-time AI conversations with Google’s Realtime LLM

Noise cancellation via LiveKit BVC plugin

Video + audio room support with RoomInputOptions

Customizable agent instructions (prompts.py)

Secure environment variable handling with dotenv

Easy-to-run CLI commands (download-files, console, dev)

Tech Stack

Python 3.10+

LiveKit Agents SDK

Google Realtime API

dotenv for environment management

Asyncio for concurrency

Noise Cancellation Plugin (LiveKit BVC)

Installation

Clone the repo and install dependencies:

git clone https://github.com/yourusername/ai-voice-agent.git
cd ai-voice-agent


Create and activate a virtual environment:

python -m venv venv
.\venv\Scripts\activate


Upgrade pip and install dependencies:

python -m pip install --upgrade pip setuptools wheel
python -m pip install -r requirements.txt

Environment Variables

Create a .env file in the project root with your credentials:

LIVEKIT_URL=your_livekit_url
LIVEKIT_API_KEY=your_livekit_api_key
LIVEKIT_API_SECRET=your_livekit_api_secret
GOOGLE_API_KEY=your_google_api_key
GMAIL_APP_PASSWORD=your_gmail_app_password
GMAIL_USER=your_gmail_address


Get LiveKit Keys

Get Google API Key

Generate Gmail App Password

Available Scripts

python agent.py download-files – Download required assets

python agent.py console – Start interactive console mode

python .\agent.py dev – Run in development mode

Demo

Check out the LiveKit Playground
 to explore agent capabilities.