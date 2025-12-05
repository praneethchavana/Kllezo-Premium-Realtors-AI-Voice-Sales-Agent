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
git clone https://github.com/yourusername/kllezo-premium-realtors-voice-agent.git
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

3. Frontend Setup
cd frontend
npm install
npm run dev
