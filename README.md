[# Kllezo-Premium-Realtors-AI-Voice-Sales-Agent
A browser-based AI voice call experience where users talk to “Aditya,” a luxury real-estate sales agent. Uses AssemblyAI for speech-to-text, Murf for TTS, and OpenRouter LLM for smart sales conversations. Built with React + Node.js for a realtime, human-like calling simulation.
]

Kllezo Premium Realtors – AI Voice Sales Agent

A browser-based AI voice-call simulation where users talk to Aditya, a premium Mumbai real estate sales executive.
Built using:

Murf Falcon (Gen2) for ultra-fast TTS

AssemblyAI for real-time speech-to-text

OpenRouter LLMs for conversation logic

React + Node.js full-stack

🚀 Features

Real-time microphone input

AI responds with Murf-generated speech

AssemblyAI-powered transcription

Smart objection handling & premium sales persona

Full call UI with transcript

Secure API key handling (env vars)

🛠️ Tech Stack
Frontend:

React + Vite

Web Audio API

Fetch API

Backend:

Node.js + Express

AssemblyAI STT

Murf Gen2 TTS

OpenRouter LLM

📦 Setup Instructions
1. Clone the repo
git clone Kllezo Premium Realtors – AI Voice Sales Agent

A browser-based AI voice-call simulation where users talk to Aditya, a premium Mumbai real estate sales executive.
Built using:

Murf Falcon (Gen2) for ultra-fast TTS

AssemblyAI for real-time speech-to-text

OpenRouter LLMs for conversation logic

React + Node.js full-stack

🚀 Features

Real-time microphone input

AI responds with Murf-generated speech

AssemblyAI-powered transcription

Smart objection handling & premium sales persona

Full call UI with transcript

Secure API key handling (env vars)

🛠️ Tech Stack
Frontend:

React + Vite

Web Audio API

Fetch API

Backend:

Node.js + Express

AssemblyAI STT

Murf Gen2 TTS

OpenRouter LLM

📦 Setup Instructions
1. Clone the repo
git clone (https://github.com/praneethchavana/Kllezo-Premium-Realtors-AI-Voice-Sales-Agent)
cd kllezo-premium-realtors-voice-agent

2. Backend Setup
cd backend
npm install


Copy .env.example → .env:

PORT=5000
ASSEMBLYAI_API_KEY=your_key
MURF_API_KEY=your_key
MURF_VOICE_ID=en-IN-eashwar
OPENROUTER_API_KEY=your_key
OPENROUTER_MODEL=openai/gpt-oss-20b


Run backend:

npm run dev

3. Frontend Setup
cd frontend
npm install
npm run dev
cd kllezo-premium-realtors-voice-agent

2. Backend Setup
cd backend
npm install


Copy .env.example → .env:

PORT=5000
ASSEMBLYAI_API_KEY=your_key
MURF_API_KEY=your_key
MURF_VOICE_ID=en-IN-eashwar
OPENROUTER_API_KEY=your_key
OPENROUTER_MODEL=openai/gpt-oss-20b


Run backend:

npm run dev








:

🔊 How the Voice Agent Works
1️⃣ User speaks

Microphone → AssemblyAI → text transcription

2️⃣ AI responds

Transcribed text → OpenRouter (gpt-oss-20b free model)

3️⃣ Voice output

Agent’s text → Murf Gen2 TTS → playable audio

4️⃣ Conversation UI

Chat bubbles + audio playback simulate a real phone call.

🧪 Local Testing Checklist
Feature	Status
ASR (AssemblyAI)	✔️ Working
LLM (OpenRouter)	✔️ Working
Murf TTS	✔️ gen2 supported
Audio playback	✔️ Browser tested
Secure .env	✔️ No keys exposed

3. Frontend Setup
cd frontend
npm install
npm run dev
