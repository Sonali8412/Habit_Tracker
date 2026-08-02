# 🚀 AI Habit Tracker

<div align="center">

# 🤖 AI Habit Tracker

### Build habits that stick with AI-powered motivation.

Track habits, monitor progress, maintain streaks, and receive personalized AI-generated encouragement—all in one modern web application.

### 🌐 Live Demo

👉 **https://ai-habit-tracker-nlp8.onrender.com**

---

![React](https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js)
![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb)
![JWT](https://img.shields.io/badge/JWT-Authentication-orange?style=for-the-badge)

</div>

---

# ✨ Overview

AI Habit Tracker is a full-stack MERN application that helps users build long-lasting habits through intelligent tracking and AI-powered motivation.

Users can securely create an account, manage habits, maintain daily streaks, analyze progress, and receive personalized motivational responses generated using Google's Gemini AI.

---

# ✨ Features

- 🔐 JWT Authentication
- 👤 User Registration & Login
- ✅ Create, Edit & Delete Habits
- 📅 Daily Habit Tracking
- 🔥 Streak Tracking
- 📊 Progress Dashboard
- 🤖 AI-Powered Motivation
- 🌙 Modern Responsive UI
- ⚡ Fast Vite Frontend
- ☁️ Fully Deployed on Render

---

# 🛠 Tech Stack

## Frontend

- React.js
- Vite
- Axios
- React Router
- Tailwind CSS

## Backend

- Node.js
- Express.js
- MongoDB Atlas
- JWT Authentication
- Gemini AI API

---

# 📂 Project Structure

```
AI_Habit_Tracker
│
├── Frontend
│   ├── public
│   ├── src
│   ├── .env
│   └── package.json
│
├── Backend
│   ├── config
│   ├── controllers
│   ├── middleware
│   ├── models
│   ├── routes
│   ├── utils
│   ├── server.js
│   └── package.json
│
└── README.md
```

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/AI_Habit_Tracker.git
```

Move into project

```bash
cd AI_Habit_Tracker
```

Install Backend

```bash
cd Backend

npm install
```

Install Frontend

```bash
cd ../Frontend

npm install
```

---

# ⚙️ Environment Variables

## Backend

```env
PORT=8000

MONGO_URI=your_mongodb_uri

JWT_SECRET=your_secret

JWT_EXPIRES_IN=365d

CLIENT_URL=http://localhost:5173

GEMINI_API_KEY=your_api_key

GEMINI_MODEL=gemini-3.5-flash
```

---

## Frontend

```env
VITE_API_URL=http://localhost:8000/api
```

---

# ▶️ Run Project

Backend

```bash
cd Backend

npm run dev
```

Frontend

```bash
cd Frontend

npm run dev
```

---

# 🌐 Deployment

| Service | Platform |
|----------|----------|
| Frontend | Render Static Site |
| Backend | Render Web Service |
| Database | MongoDB Atlas |

---

# 📡 API Endpoints

## Authentication

```
POST /api/auth/register

POST /api/auth/login

GET /api/auth/me
```

---

## Habits

```
GET /api/habits

POST /api/habits

PUT /api/habits/:id

DELETE /api/habits/:id
```

---

## Logs

```
GET /api/logs

POST /api/logs
```

---

## AI

```
POST /api/ai
```

---

# 🔒 Security

- JWT Authentication
- Password Hashing
- Protected API Routes
- Environment Variables
- Secure MongoDB Atlas Connection
- CORS Configuration

---

# 📈 Future Enhancements

- Google OAuth Login
- Email Verification
- Habit Reminder Notifications
- Weekly & Monthly Reports
- Calendar View
- AI Chat Assistant
- Mobile App
- Dark / Light Theme

---

---

# 🤝 Contributing

Contributions are welcome.

1. Fork the project

2. Create a feature branch

```bash
git checkout -b feature/New Feature
```

3. Commit changes

```bash
git commit -m "Added New Feature"
```

4. Push

```bash
git push origin feature/NewFeature
```

5. Open a Pull Request

---

# ⭐ Show Your Support

If you like this project, don't forget to ⭐ Star the repository.

---

# 👩‍💻 Developer

## Sonali Kumari

** MERN Stack Developer**

### 🌐 Live Project

https://ai-habit-tracker-nlp8.onrender.com

---

<div align="center">


⭐ Thanks for visiting this repository! ⭐

</div>
