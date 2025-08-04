# 🛡️ BrimmAuth - Login System with FastAPI

A beginner-to-intermediate full stack login system, built from scratch to practice:

- 🐍 Python logic
- 🔌 API handling
- 🗃️ Database integration
- 🎨 Basic UI design

---

## 🗺️ Project Plan

| Feature | Description |
|--------|-------------|
| 👤 Signup form | User enters name, email, password |
| 📤 POST request | Send form data to backend |
| 🛡️ Password handling | Store password securely (hashed) |
| 🗃️ Database | Save users (name, email, password) |
| 🔐 Login form | Backend verifies credentials |
| 🔓 Auth success | Return JSON success or failure |
| 🌐 Frontend | Optional UI form (HTML, Tailwind, or React) |

---

## ⚙️ Tech Stack

| Part | Tool |
|------|------|
| Backend | FastAPI |
| Database | SQLite → Supabase (later) |
| Frontend | HTML (or Tailwind / React) |
| Hashing | passlib[bcrypt] |
| Auth Flow | Session logic → JWT (upgrade path) |

---

## 🚦 Dev Milestones

- ✅ Step 1 – Project setup & FastAPI boilerplate
- ⏳ Step 2 – `POST /signup` endpoint
- ⏳ Step 3 – Connect to SQLite with SQLAlchemy
- ⏳ Step 4 – `POST /login` + password check
- ⏳ Step 5 – Return tokens or messages
- ⏳ Step 6 – (Optional) UI form to test
- ⏳ Step 7 – (Optional) BrimmBot memory integration 😎

---

## 🧪 Try It Locally

```bash
git clone https://github.com/your-username/brimm-auth-api.git
cd brimm-auth-api
pip install -r requirements.txt
uvicorn main:app --reload
