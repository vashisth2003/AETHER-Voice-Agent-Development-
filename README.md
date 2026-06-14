README.md

Markdown
# Aether Voice Agent 🎙️

A lightning-fast, voice-enabled AI assistant powered by Groq and LangChain. 

Aether pairs a highly responsive FastAPI backend with a sleek vanilla HTML/JS frontend, utilizing the browser's native Web Speech API for real-time voice interactions. It autonomously uses tools like web search, math calculators, and real-time clocks to deliver instant, hands-free answers.

## Features
- **Real-Time Voice:** Web Speech API integration for instant STT (Speech-to-Text) and TTS (Text-to-Speech).
- **Tool Calling:** Powered by Llama-3.3-70b-versatile, capable of web searches (DuckDuckGo), math calculations, and checking the time.
- **Show Reasoning Mode:** See the AI's "thought process" and backend tool execution steps.
- **Customizable:** Adjust voice pitch and speed; preferences save to Local Storage.

## Setup Instructions

1. **Clone the repo:** `git clone https://github.com/yourusername/aether-voice-agent.git`
2. **Install backend dependencies:** `pip install -r requirements.txt`
3. **Set your Groq API key:** Add your key to the `.env` file.
4. **Run the backend:** `cd backend && uvicorn main:app --reload`
5. **Run the frontend:** Open `frontend/index.html` in your browser (preferably via a live server like VS Code Live Server).
