# 🎓 MatricBuddy

**An AI-powered study platform for Matric learners.**

MatricBuddy is a web application that helps Grade 12 learners find past examination papers, access them from their original sources, and use AI to understand difficult questions and practise for exams.

## 🚀 Features

* 🔎 Search for Matric past papers
* 📚 Filter papers by subject, year, paper and exam session
* 🔗 Access papers through their original sources
* 🤖 AI-powered study assistant
* 💡 Get explanations and hints for difficult questions
* 📝 Generate practice questions
* ❤️ Save useful papers
* 👤 Student accounts
* 📱 Responsive design for mobile, tablet and desktop
* 🛠️ Admin paper management

## 🧠 How It Works

MatricBuddy follows a simple learning process:

**Find → Understand → Practise**

1. Find a past paper.
2. Open the paper from its original source.
3. Ask the AI Tutor for help with difficult questions.
4. Practise similar questions and improve your understanding.

## 🛠️ Tech Stack

### Frontend

* React
* Vite
* JavaScript
* React Router
* Axios
* Pure CSS

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT Authentication

### AI

* Gemini API

### Deployment

* Netlify
* Render
* MongoDB Atlas

## 📂 Project Structure

```text
MatricBuddy/
│
├── client/       # React frontend
│
├── server/       # Express backend
│
├── README.md
└── .gitignore
```

## ⚙️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/matricbuddy.git
cd matricbuddy
```

### 2. Install dependencies

Frontend:

```bash
cd client
npm install
```

Backend:

```bash
cd ../server
npm install
```

### 3. Set up environment variables

Create a `.env` file inside the `server` folder:

```env
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
GEMINI_API_KEY=your_gemini_api_key
CLIENT_URL=http://localhost:5173
```

Create a `.env` file inside the `client` folder:

```env
VITE_API_URL=http://localhost:5000/api
```

### 4. Run the project

Start the backend:

```bash
cd server
npm run dev
```

Start the frontend:

```bash
cd client
npm run dev
```

## 🎯 Project Goal

The goal of MatricBuddy is to make exam preparation easier by bringing **past papers, AI assistance and practice tools** together in one platform.

Instead of simply finding a question paper, learners can use MatricBuddy to **learn from it**.

## 🔮 Future Plans

* AI-generated quizzes
* Personalised study plans
* Student progress tracking
* AI-powered question analysis
* Topic recommendations
* More subjects and past papers
* Advanced AI tutoring using RAG
* Improved student dashboard

## 📸 Screenshots

*Add screenshots of the application here.*

## 👨‍💻 Author

**[Your Name]**

Built as a student software development project.

## 📄 License

This project is intended for educational purposes.

---

⭐ If you find MatricBuddy interesting, consider giving the repository a star!
