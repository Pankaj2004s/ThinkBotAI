# ThinkBotAI

A full-stack AI chat application built with React and Node.js. Users can start conversations with an AI, switch between multiple chat threads, and their history is saved across sessions using MongoDB.

Live Demo: https://think-bot-ai-liart.vercel.app
Backend: https://thinkbotai-backend.onrender.com
GitHub: https://github.com/Pankaj2004s/ThinkBotAI

## Features

- Chat with an AI powered by Groq API
- Create multiple chat threads and switch between them
- Chat history saved to MongoDB — persists across sessions
- Markdown rendering in AI responses with code syntax highlighting
- Loading spinner while waiting for AI response
- Delete individual chat threads
- Clean separation of frontend and backend

## Tech Stack

**Frontend:** React 19, Vite, react-markdown, highlight.js, react-spinners, uuid

**Backend:** Node.js, Express.js, ES Modules

**Database:** MongoDB, Mongoose, MongoDB Atlas

**AI:** Groq API with OpenAI-compatible SDK (model: openai/gpt-oss-120b)

**Other:** CORS, dotenv, nodemon

## Project Structure
ThinkBotAI/
├── frontend/ # React + Vite app
└── backend/ # Node.js + Express API server


## Installation

### Backend

1. Clone the repo and go to the backend folder

git clone https://github.com/Pankaj2004s/ThinkBotAI.git
cd ThinkBotAI/backend


2. Install dependencies

npm install


3. Create a `.env` file and add:

OPENAI_API_KEY=your_groq_api_key
MONGODB_URI=your_mongodb_connection_string


4. Start the backend server

node server.js


Server runs on `http://localhost:8080`

### Frontend

1. Go to the frontend folder

cd ThinkBotAI/frontend


2. Install dependencies

npm install


3. Start the frontend

npm run dev


4. Open `http://localhost:5173` in your browser

## Future Work

- Add user authentication so each user has their own separate chat history
- Add ability to rename chat threads
- Support for selecting different AI models
- Improve UI with better styling and mobile responsiveness

## Author
Pankaj Sharma