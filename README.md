#  AI Chatbot Assistant

A simple full-stack web application featuring an AI-powered chatbot using the Gemini API (or OpenAI as fallback). Built with **React + Vite**, **Node.js**, **Express**, and styled using **vanilla CSS**.

## Project Overview

This chatbot assistant allows users to interact with an AI model via a chat-style interface. The frontend displays user and AI messages in real time, while the backend handles the message processing using the Gemini API.

## 🛠️ Technologies Used

- **Frontend**: React + Vite, Vanilla CSS
- **Backend**: Node.js, Express
- **AI API**: Gemini API
- **HTTP Client**: Axios

---

## 📦 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/ai-chatbot-assistant.git
cd ai-chatbot-assistant
```
2. Install Dependencies
Frontend
```bash
cd frontend
npm install
```

Backend
```bash
cd server
npm install
```

3. Set Up API Key
For Gemini API:
Go to Gemini Console
Get your API Key
Create a .env file in the server folder:
```bash
GEMINI_API_KEY=Paste_gemini_api_key_here
PORT = 5000
```
4. Start the Servers
```bash
cd server
npm start
```

Frontend (on port 5173)
```bash
cd client
npm run dev
```

## API Endpoint Documentation
POST /api/chat - Sends a user message to the backend and receives an AI-generated reply.

Request Body (JSON)
```bash
{
  "message": "What is AI?"
}
```
Successful Response (JSON)
```bash
{
  "response": "AI stands for Artificial Intelligence, the simulation of human intelligence by machines."
}
```

📷 Demo
A 2-minute demo video showing message interaction and response rendering is available here:
🔗 Demo Video - Google Drive Link
Demo Screenshots-

❗ Assumptions & Limitations
Gemini API key must be valid and active (free tier is supported).
This is a minimal proof-of-concept project.
No authentication or persistent chat history implemented.
No rate-limiting or error handling for abuse of API quota.

📁 Folder Structure
```bash

ChatBot_task/
├── client/             
│   ├── App.js
│   ├── App.css
│   └── ...
├── server/               
│   ├── index.js
│   ├── routes/
│   └── .env
├── README.md
└── package.
```
🧾 License
This project is for demonstration purposes only.


