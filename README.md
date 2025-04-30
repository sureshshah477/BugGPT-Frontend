# 🐞 BugGPT - Smart Code Debugging Assistant

BugGPT is a smart multi-language code analysis assistant that automatically detects and reviews your code for errors, bugs, and improvements using **Google Gemini Flash 2.0** API.

No need to select a language — just paste your code, click **Review**, and get helpful insights instantly. It's built for developers, students, and coders who want a quick and intelligent debugging assistant.

🌐 [Live Demo](https://bug-gpt-front-git-main-suresh-shahs-projects.vercel.app)

---

## 📌 Features

- 🔍 **Automatic Language Detection** (No manual selection)
- 🧠 **AI-Powered Review** using Gemini Flash 2.0 by Google
- ⚡ **Instant Feedback** on syntax issues, logical errors, and suggestions
- 💻 Paste any code (C, C++, Python, Java, etc.)
- 🖼️ Clean and responsive UI (React + TailwindCSS)
- 🌐 Fully deployed on **Vercel**

---

## ⚙️ Tech Stack

| Area        | Technology              |
|-------------|--------------------------|
| Frontend    | React.js, TailwindCSS    |
| Backend     | Node.js, Express.js      |
| AI Model    | Gemini Flash 2.0 API     |
| Deployment  | Vercel                   |

---

## 🧠 How It Works

1. Paste your code into the editor.
2. Click the **Review** button.
3. The app automatically detects the language.
4. The code is sent to the backend, which calls the Gemini Flash 2.0 API.
5. The response includes:
   - 🐛 Detected Errors
   - 🛠️ Suggestions
   - 🔁 Improved Code (if applicable)

---

---

## 🚀 Local Setup Instructions

> Make sure Node.js and npm are installed.

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/BugGPT.git
cd BugGPT
cd backend
npm install
# Add your GEMINI_API_KEY in a .env file
npm start
cd frontend
npm install
npm run dev

