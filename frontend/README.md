# ThinkBotAI

ThinkBotAI is a full-stack AI chatbot application built using React, Node.js, Express, MongoDB, and Groq API. It allows users to create multiple chat threads, switch between conversations, and receive AI-generated responses with Markdown and code syntax highlighting support.

## Features

- Multiple Chat Threads
- Thread Switching
- Delete Thread Functionality
- AI Responses using Groq API
- MongoDB Atlas Integration
- Auto Scroll Support
- Typing Animation
- Markdown Rendering
- Code Syntax Highlighting
- Responsive User Interface
- Custom Sidebar Navigation

## Tech Stack

### Frontend

- React.js
- Vite
- CSS
- React Markdown
- Rehype Highlight
- UUID

### Backend

- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- Groq API

## Project Structure

```text
ThinkBotAI
│
├── backend
│   ├── models
│   ├── routes
│   ├── utils
│   └── server.js
│
└── frontend
    ├── src
    │   ├── App.jsx
    │   ├── Chat.jsx
    │   ├── ChatWindow.jsx
    │   ├── Sidebar.jsx
    │   └── MyContext.jsx
```

## Installation

### Clone the Repository

```bash
git clone <repository-url>
```

### Backend Setup

```bash
cd backend
npm install
npm run dev
```

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

## Environment Variables

Create a `.env` file inside the backend directory and add:

```env
MONGO_URL=your_mongodb_connection_string
GROQ_API_KEY=your_groq_api_key
```

## Future Improvements

- Light/Dark Theme
- Voice Support
- Dropdown Settings
- User Authentication

## Author

Pankaj Sharma