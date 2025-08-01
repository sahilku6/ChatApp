# 🧠 Chat App with AI

A collaborative MERN stack project workspace featuring real-time chat, AI-powered code generation, and in-browser live code editing using WebContainers.

---

## 🚀 Features

* 🔐 **User Authentication** – Secure user registration and login.
* 👥 **Project Collaboration** – Create projects, add collaborators, and manage shared files.
* 💬 **Real-time Chat** – Chat live with project teammates via WebSockets.
* 🤖 **AI Assistant** – Mention `@ai` to receive intelligent suggestions (file structures, code snippets) from **Gemini AI**.
* 💻 **Live Code Editor** – Write and run code directly in the browser using **WebContainers**.
* 📁 **File Tree Management** – Edit files collaboratively with real-time updates.

---

## 💠 Tech Stack

### Frontend

* React
* Vite
* Tailwind CSS
* Socket.io-client
* WebContainers

### Backend

* Node.js
* Express
* MongoDB
* Socket.io
* Google Generative AI (Gemini API)

---

## 📂 Project Structure

```bash
├── backend/               # Express server and APIs
├── frontend/              # React app (Vite)
└── README.md
```

---

## ⚙️ Getting Started

### Prerequisites

* Node.js (v18+ recommended)
* npm
* MongoDB (local or Atlas)
* Google Gemini API key

---

### 📦 Installation

#### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/Chat-App-with-ai.git
cd Chat-App-with-ai
```

---

#### 2. Setup Backend

```bash
cd backend
npm install
```

Create a `.env` file in the `backend/` directory:

```env
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
GOOGLE_AI_KEY=your_google_gemini_api_key
REDIS_HOST=localhost
REDIS_PORT=6379
REDIS_PASSWORD=your_redis_password_if_any
```

---

#### 3. Setup Frontend

```bash
cd ../frontend
npm install
```

Create a `.env` file in the `frontend/` directory:

```env
VITE_API_URL=http://localhost:3000
```

---

#### 4. Run the App

```bash
# In backend/
npm run dev

# In frontend/
npm run dev
```

---

### 🔗 Access the App

* **Frontend**: [http://localhost:5173](http://localhost:5173)
* **Backend**: [http://localhost:3000](http://localhost:3000)

---
