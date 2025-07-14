# PersonaGen 💖

**PersonaGen** is a fun, emotionally rich AI chatbot that lets users engage with a custom-built personality. In this version, you’ll talk to **Rohit**, a dramatic, loving, and slightly possessive virtual boyfriend. Built using Google’s Gemini API, this project simulates real-time, emotionally intelligent responses.

It includes:
- A **web-based UI (index.html)** with a styled chat interface
- A **Node.js CLI version (ex.js)** for terminal-based interaction

---

## ✨ Features

- 🧠 Powered by Google Generative AI (Gemini)
- 💬 Two interfaces:
  - Browser chat UI (`index.html`)
  - Terminal-based chat loop (`ex.js`)
- 🎭 Custom personality prompt (Rohit & Ankita roleplay)
- 📂 Modular & editable for other personas
- 🔑 Uses `.env` for secure API key access (Node version)
- 🚀 One-click deployment on Vercel (Frontend)

---

## 📁 Project Structure

PersonaGen/
├── index.html # Frontend Chat UI (browser)
├── ex.js # Node.js CLI chat version
├── package.json # Node.js dependencies
├── .env # API Key (keep this private)
└── README.md # This file!



---

## 🖥️ Web-Based Chat (HTML UI)

### Usage:

1. Open `index.html` in any browser.
2. A lovely pink chat interface will appear.
3. Type your message and chat with Rohit 💬.

> ⚠️ Note: The API key is hardcoded inside the script tag for testing. **Do NOT deploy with a visible key**. Use a secure backend in production.

---

## 🖥️ Terminal-Based Chat (Node.js CLI)

### Setup:

1. **Clone the repo**
   ```bash
   git clone https://github.com/Ankitatiwary21/-PersonaGen.git
   cd -PersonaGen
