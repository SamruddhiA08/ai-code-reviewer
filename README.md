# 🚀 AI Code Reviewer (MERN + Google Gemini)

An **AI-powered code reviewer** built with the **MERN stack** and integrated with **Google Generative AI**.
This project analyzes code, suggests improvements, and enhances development efficiency.

---

## ✨ Features

* 🔍 **AI-Powered Code Review** — get instant suggestions & improvements.
* ⚡ **MERN Stack** — Express backend + React frontend.
* 🎨 **Syntax Highlighting** with Prism.js.
* 📝 **Markdown Rendering** for AI responses.
* 🌐 **CORS + Axios Integration** — smooth frontend-backend communication.
* 🎛️ **Refactored API Handling** — uses POST request structure for cleaner flow.

---

## 🛠️ Tech Stack

**Frontend**

* React (Vite)
* Prism.js (syntax highlighting)
* Axios
* Markdown renderer

**Backend**

* Node.js + Express
* Google Generative AI SDK (`@google/generative-ai`)
* CORS + dotenv

---

## 📂 Project Structure

```
AI-CODE-REVIEWER/
│
├── Backend/         # Express server + AI integration
│   ├── server.js
│   ├── package.json
│   └── .env (ignored in git)
│
├── Frontend/        # React (Vite) frontend
│   ├── src/
│   ├── package.json
│   └── vite.config.js
│
└── README.md
```

---

## ⚙️ Setup Instructions

### 🔹 1. Clone the repository

```bash
git clone https://github.com/your-username/ai-code-reviewer.git
cd ai-code-reviewer
```

### 🔹 2. Backend Setup

```bash
cd Backend
npm install
```

Create a `.env` file inside `Backend/`:

```
GEMINI_API_KEY=your_api_key_here
PORT=4000
```

Run backend:

```bash
npm run start
```

Server should run on: `http://localhost:4000`

---

### 🔹 3. Frontend Setup

```bash
cd ../Frontend
npm install
npm run dev
```

Frontend runs at: `http://localhost:5173`

---

## 📸 Preview

<img width="1920" height="1021" alt="Screenshot 2025-09-13 185431" src="https://github.com/user-attachments/assets/eedb5c21-1e63-4434-aae6-5222b8a2260d" />


---

## 👨‍💻 Author

**Samm**
📌 Aspiring Software Developer | MERN + AI Projects

✨ If you like this project, give it a ⭐ on GitHub!
