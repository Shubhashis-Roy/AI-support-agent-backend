# AI Support Chatbot

- Description: The application allows users to chat with a support agent, persists conversations, and restores chat history on reload using a session-based approach.

## How to setup and run the project

### Frontend

- Add .env file
- env file (please no need to edit just copy this and past on .env file):

  - VITE_API_DEV_URL = http://localhost:4000/api

- Install node packages: `npm i`
- Run the project: `npm run dev`

#### Tech stack

- React
- Vite
- TypeScript

### Backend

- Add .env file
- env file (please no need to edit just copy this and past on .env file):

  - PORT = 4000
  - SUPABASE_URL = 'https://tdmlvpjcyocwpvxzyuof.supabase.co'
  - SUPABASE_ANON_KEY = 'sb_publishable_sSAnpDzOZMZGf9H8yH-NVg_l5vTuEXp'
  - GROQ_API_KEY = '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'

- Install node packages: `npm i`
- Run the project: `npm run dev`

#### Tech stack

- Node.js
- Express
- TypeScript
- Supabase (PostgreSQL)

### AI / LLM

- **Groq API**
- Model: `llama-3.1-8b-instant`

Groq was chosen because it provides a **free**, fast, and production-grade LLM suitable for interview demos without requiring billing.

---

## Features

- AI-powered customer support chat
- Session-based conversations (reload-safe)
- Persistent chat history using PostgreSQL (Supabase)
- Graceful handling of invalid input and AI/API failures
- Clean separation of frontend and backend
- Free LLM integration using **Groq (LLaMA 3.1)**
