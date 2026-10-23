# PranaPulse 🧘‍♂️

PranaPulse is a basic AI-powered yoga assistant web application built as a first-year college hackathon project. It combines a simple yoga-themed website with an AI chatbot that provides yoga-related suggestions based on users' concerns.

## ✨ Features

- **Yoga Landing Page** — A simple homepage introducing the project.
- **AI Chat Assistant** — Ask Prana answers yoga-related questions through an AI chatbot.
- **Yoga Assistant Chatbot** — An additional chat interface for personalized yoga suggestions.
- **Responsive UI** — Built with React and Tailwind CSS.
- **Page Navigation** — Separate Home, About, and AI chat pages.
- **Animations** — Basic UI animations using Framer Motion.

## 🛠️ Tech Stack

**Frontend**
- React
- Vite
- Tailwind CSS
- Framer Motion
- React Router
- Axios

**Backend**
- Node.js
- Express.js
- Groq API
- Llama 3 model

## 📁 Project Structure

```text
PranaPulse/
├── Client/
│   ├── src/
│   │   ├── components/
│   │   │   ├── about/
│   │   │   ├── ai/
│   │   │   ├── Body/
│   │   │   ├── common/
│   │   │   ├── constants/
│   │   │   └── yogaChatbot/
│   │   ├── App.jsx
│   │   └── index.css
│   └── package.json
│
└── Server/
    ├── config/
    ├── controllers/
    ├── routes/
    ├── utils/
    └── package.json
```

## 🚀 Getting Started

### Prerequisites

- Node.js and npm
- A Groq API key

### 1. Clone the repository

```bash
git clone <your-repository-url>
cd PranaPulse
```

### 2. Set up the backend

```bash
cd Server
npm install
```

Create a `.env` file in the project root directory:

```env
GROQ_API_KEY=your_groq_api_key
```

Start the backend:

```bash
node utils/server.js
```

The backend runs on `http://localhost:3000`.

### 3. Set up the frontend

Open a new terminal:

```bash
cd Client
npm install
```

Create a `.env` file inside the `Client` directory:

```env
VITE_SERVER_URL=http://localhost:3000
```

Start the frontend:

```bash
npm run dev
```

Open the local URL displayed by Vite in your browser.

**Note:** The project uses an older Llama 3 model identifier. Depending on current Groq API availability, you may need to update the model name in the backend.

## 🎓 Project Background

PranaPulse was developed as a first-year college hackathon project to explore basic web development and AI chatbot integration. It represents an early learning project rather than a production-ready application.

---

*Built as a college hackathon project to explore React, backend development, and AI-powered yoga assistance.*
