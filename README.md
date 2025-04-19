# 🛡️ SkillForge

**SkillForge** is an advanced AI-powered mock interview platform designed to help developers prepare for technical interviews. It provides realistic interview simulations with AI-generated questions, real-time feedback, and comprehensive performance analytics.

This app is built on the **MERN stack**, integrated with **Firebase Authentication** and **OpenAI API**, featuring video recording, code execution, and detailed performance analysis.

---

## 🌐 Live Preview

> _Coming Soon..._

---

## 🚀 Tech Stack

### Frontend
- **React** (Vite) — fast and modern frontend framework
- **TailwindCSS** — utility-first CSS framework
- **React Router** — SPA routing
- **Axios** — API requests
- **Web APIs** — `getUserMedia`, `MediaRecorder`, Code Editor APIs
- **Context API / Redux (optional)** — state management

### Backend
- **Node.js + Express.js** — REST API backend
- **OpenAI API** — AI interview conductor
- **Firebase Admin SDK** — handle user validation
- **Firestore** — flexible NoSQL cloud database
- **Firebase Storage** — store interview recordings

---

## ✨ Core Features

### 🧑‍💻 User Features

- **Secure Login/Register** via Firebase Auth
- **Interview Categories:**
  - Frontend Development
  - Backend Development
  - Full Stack Development
  - Data Structures & Algorithms
  - System Design
- **Interview Experience:**
  - AI-powered interviewer
  - Real-time code execution
  - Video recording of responses
  - Voice-based interaction
- **Performance Analysis:**
  - Detailed feedback on responses
  - Code quality assessment
  - Communication skills evaluation
  - Body language analysis
- **Learning Resources:**
  - Personalized improvement tips
  - Common interview patterns
  - Best practices guide

---

### 🛠️ Admin Panel

- **Role-based access:** Admin and User
- **Question Bank Management:**
  - Customize AI prompts
  - Add interview scenarios
  - Set difficulty levels
- **Analytics Dashboard:**
  - User performance metrics
  - Popular interview topics
  - Success rate analysis
- **Content Management:**
  - Learning resources
  - Interview templates
  - Feedback patterns

---

## 🔐 Interview System

- **Video Recording:**
  - Uses `MediaRecorder` API
  - Stores interview sessions
  - Supports playback review
- **Code Editor:**
  - Syntax highlighting
  - Multiple language support
  - Real-time execution
- **AI Integration:**
  - Dynamic question generation
  - Response evaluation
  - Personality assessment
- **Analytics Engine:**
  - Performance scoring
  - Improvement tracking
  - Detailed reports

---

## 📁 Folder Structure

skillforge/
├── client/                         # Frontend (React + Vite + Tailwind)
│   ├── public/                     # Static files like index.html, favicon
│   └── src/
│       ├── assets/                 # Logos, icons, images
│       ├── components/             # Reusable UI components (VideoRecorder, CodeEditor, etc.)
│       ├── context/                # Context providers (AuthContext, InterviewContext)
│       ├── pages/                  # Route-based pages (Home, Interview, Dashboard)
│       ├── routes/                 # App routes (PrivateRoutes, PublicRoutes)
│       ├── services/               # API handlers using Axios
│       ├── utils/                  # Utility functions (AI helpers, analytics, formatting)
│       ├── App.jsx                 # Main application wrapper
│       └── main.jsx                # Vite entry point
│
├── server/                         # Backend (Node.js + Express + Firebase Admin)
│   ├── config/                     # Firebase Admin SDK and OpenAI config
│   ├── controllers/                # Route logic (Interview, AI, Analytics)
│   ├── middleware/                 # Auth middleware, AI processor, error handler
│   ├── models/                     # Schema helpers for Firestore
│   ├── routes/                     # API route definitions
│   ├── utils/                      # AI prompts, analysis helpers, formatters
│   ├── .env                        # Backend environment variables
│   └── server.js                   # Entry point of Express server
│
├── firebase.json                   # Firebase deployment and emulator config
├── firestore.rules                 # Firestore security rules
├── README.md                       # Project documentation
└── package.json                    # Project metadata and scripts
