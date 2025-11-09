# 🧠 SudoBits  
Real-time communication app with **sign language detection**, **chat**, and **video calls**. 

It integrates modern web UI with robust backend services and model hooks to enable accessible, efficient and interactive experiences.


## 🚀 Overview  
HackVerse combines AI and real-time communication to make conversations more inclusive and interactive.  

It brings together:
- A machine learning (ML) model (via **FastAPI**) that recognises common sign‐language gestures (e.g., “Hello”, “I Love You”, “Thank You”).

- A frontend UI built in **React + Vite and Tailwind** for chat and video calls.

- A backend API layer (**Node.js/Express**) for authentication, chat logic and database integration.
  
This enables users to engage via text, video, and sign-language detection all within a single platform.

## 📂 Project Structure  
```

HackVerse/
├── backend/    # Express API (auth, chat, DB)
├── frontend/   # React UI (chat, video, 3D visuals)
└── model/      # FastAPI ML model (sign detection)

````

## ⚙️ Setup & Run  

### 🖥️ Backend  
```bash
cd backend
npm install
npm run dev
````

### 💻 Frontend

```bash
cd frontend
npm install
npm run dev
```

### 🤖 Model

```bash
cd model
python -m venv .venv
.venv\Scripts\activate  # for Windows
# On macOS/Linux: source .venv/bin/activate 
pip install -r requirements.txt
uvicorn src.api:app --reload
```

## 🧩 Tech Stack

* **Frontend:** React + Vite, Lucide React, Tanstack, Stream Chat/Video, Clerk, Tailwind, Three Fiber
* **Backend:** Node.js, Express, MongoDB, Inngest, Sentry
* **Model:** FastAPI, PyTorch, DETR (ResNet-50), OpenCV

This setup enables real-time video/chat features, authentication, database support, and an AI model for sign detection.

## ✨ Features

✅ Real-time Chat & Video Calls

✅ Authentication via Clerk

✅ Sign Language Detection (Like “Hello”, “I Love You”, “Thank You”)

✅ Interactive 3D UI

and many more...

