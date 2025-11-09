
---

```markdown
# 🧠 HackVerse  
Real-time communication app with **sign language detection**, **chat**, and **video calls**.

## 🚀 Overview  
HackVerse combines AI and real-time communication to make conversations more inclusive.  
It features a **FastAPI ML model** for detecting sign language, a **React frontend** for chat/video, and a **Node.js backend** for APIs and authentication.

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
pip install -r requirements.txt
uvicorn src.api:app --reload
```

## 🧩 Tech Stack

* **Frontend:** React + Vite + Stream Chat/Video + Clerk + Tailwind + Three Fiber
* **Backend:** Node.js + Express + MongoDB + Inngest + Sentry
* **Model:** FastAPI + PyTorch + DETR (ResNet-50) + OpenCV

## ✨ Features

✅ Real-time Chat & Video Calls
✅ Authentication via Clerk
✅ Sign Language Detection (“hello”, “iloveyou”, “thankyou”)
✅ Interactive 3D UI

```

---

```
