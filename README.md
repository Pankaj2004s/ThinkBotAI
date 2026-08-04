# ThinkBotAI

A full-stack AI chatbot application where users can have conversations with an AI model. Built with React on the frontend and Node.js/Express on the backend, with MongoDB storing chat threads and history.

## Features

- Chat with an AI powered by Groq API using the llama-3.3-70b-versatile model
- Multiple chat threads — create new conversations and switch between them
- Chat history saved to MongoDB so conversations persist across sessions
- Markdown support in AI responses with syntax highlighting for code blocks
- Loading spinner while waiting for AI response
- Delete individual chat threads
- Separate frontend and backend for clean project structure

## Tech Stack

- Frontend: React 19, Vite, react-markdown, highlight.js, react-spinners, uuid
- Backend: Node.js, Express.js, ES Modules
- Database: MongoDB, Mongoose
- AI Integration: Groq API via OpenAI SDK (llama-3.3-70b-versatile)
- Other: CORS, dotenv, nodemon

## Installation

### Backend

1. Go to the backend folder

cd backend

2. Install dependencies

npm install

3. Create a .env file and add the following

OPENAI_API_KEY=your_groq_api_key
MONGODB_URI=your_mongodb_connection_string

4. Start the backend server

npm run dev

The server will run on http://localhost:8080

### Frontend

1. Go to the frontend folder

cd frontend

2. Install dependencies

npm install

3. Start the frontend

npm run dev

4. Open your browser and go to http://localhost:5173

## Future Work

- Add user authentication so each user has their own separate chat history
- Add ability to rename chat threads
- Support for selecting different AI models
- Improve UI with better styling and mobile responsiveness
