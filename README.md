# Full Stack Quiz Game with Timer 🧠⏱️

This is a full-stack quiz game built with **HTML**, **CSS**, and **JavaScript** on the frontend, and **Node.js**, **Express**, and **MongoDB** on the backend. Players can take a timed quiz, track their scores, log in, and view a global leaderboard.

---

## 🎮 Features

### ✅ Frontend
- ⏱ **Timed Questions** – Each question must be answered before the countdown finishes.
- ❓ **Multiple Choice Format** – Players select from given answer options.
- 📊 **Score Display** – Shows total correct answers at the end of the quiz.
- 📱 **Responsive UI** – Works well on desktops, tablets, and mobiles.

### ✅ Backend
- 🔐 **User Authentication** – Simple username/password-based login and signup.
- 💾 **Score Saving** – Submits and stores quiz scores in MongoDB.
- 🏆 **Leaderboard** – Fetches and displays top scores from all users.
- 🌐 **REST API** – Clean and extendable API for frontend-backend communication.

---

## 🚀 How to Play

1. Sign up or log in with a username.
2. Click **Start** to begin the quiz.
3. Read the question and select the correct option before time runs out.
4. Your score is saved and shown at the end.
5. View the **Leaderboard** to compare scores with others.

---

## 🛠 Technologies Used

### Frontend:
- **HTML**, **CSS**, **JavaScript** – Game structure, styling, and logic
- **Fetch API** – Communication with the backend

### Backend:
- **Node.js + Express** – REST API and routing
- **MongoDB + Mongoose** – Database for users and scores
- **dotenv, cors** – Environment and cross-origin management

---

## 📂 Folder Structure

```
quiz_game/
├── frontend/
│   ├── index.html
│   ├── style.css
│   └── script.js
└── backend/
    ├── index.js
    ├── models/
    │   ├── User.js
    │   └── Score.js
    └── .env
```

---

## 🔧 Getting Started

### ✅ Frontend (Local)
1. Clone the repo:
   ```bash
   git clone https://github.com/Aarti-Sharma25/quiz_game.git
   ```
2. Open `frontend/index.html` in your browser.

### ✅ Backend (Local)
1. Navigate to the backend:
   ```bash
   cd backend
   npm install
   ```
2. Create a `.env` file:
   ```env
   MONGO_URI=mongodb://localhost:27017/quizapp
   ```
3. Start the server:
   ```bash
   node index.js
   ```
4. The backend will run on `http://localhost:5000`.

---

## 📡 API Endpoints

| Endpoint           | Method | Description              |
|--------------------|--------|--------------------------|
| `/signup`          | POST   | Register a new user      |
| `/login`           | POST   | Authenticate a user      |
| `/submit`          | POST   | Submit a quiz score      |
| `/leaderboard`     | GET    | Fetch top scores         |

---

## 🌱 Future Enhancements

- ✨ JWT-based secure authentication
- ✨ Password encryption with bcrypt
- ✨ Category-based quizzes
- ✨ Persistent sessions with cookies/localStorage
- ✨ Deployment (Frontend: GitHub Pages, Backend: Render/Cyclic)

---

## 👩‍💻 Author

This project was created by **Aarti Sharma**  
NIT Kurukshetra | Aspiring Software Developer | [GitHub](https://github.com/Aarti-Sharma25)

---
