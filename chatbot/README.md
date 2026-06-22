# 🤖 AI Customer Support Chatbot

> A production-ready AI chatbot for businesses — built with **Django + Groq AI**. Deployable on any website with a single line of embed code.

![Python](https://img.shields.io/badge/Python-3.13-blue?style=flat-square&logo=python)
![Django](https://img.shields.io/badge/Django-6.0-green?style=flat-square&logo=django)
![Groq](https://img.shields.io/badge/Groq-AI-orange?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)

---

## ✨ Features

- 🤖 **AI-Powered Responses** — Groq LLaMA model for fast, accurate answers
- 💬 **Chat History** — Remembers conversation context
- 🌙 **Dark / Light Mode** — Persistent theme toggle
- ⚡ **Typing Animation** — Real-time typing indicator
- 🔒 **Embed Security** — Domain whitelist protection
- 📱 **Fully Responsive** — Works on mobile & desktop
- 🎨 **Deep Navy + Cyan Theme** — Professional UI
- 🔗 **One-Line Embed** — Add to any website instantly

---

## 📸 Screenshots

### 🌙 Dark Mode
![Dark Mode]<img width="1600" height="793" alt="dark mode" src="https://github.com/user-attachments/assets/2300fdbb-48bb-4f5b-8812-c61d61ad3dfd" />


### ☀️ Light Mode  
![Light Mode]<img width="1600" height="812" alt="light mode" src="https://github.com/user-attachments/assets/57a97206-0ba9-434d-94c1-a93ac7d93512" />


### 📱 Mobile View
![Mobile]<img width="720" height="1426" alt="mobile view" src="https://github.com/user-attachments/assets/98e8d294-43a6-4b77-92fd-cbac4606a121" />




## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Backend | Python, Django |
| AI Engine | Groq API (LLaMA 3.3) |
| Frontend | HTML, CSS, JavaScript |
| Security | Domain whitelist, CSRF protection |
| Deployment | Render.com |

---

## ⚙️ Local Setup

### 1. Clone
```bash
git clone https://github.com/Bismashoukat/AI-Customer-Support-Chatbot.git
cd AI-Customer-Support-Chatbot
```

### 2. Virtual environment
```bash
python -m venv venv
venv\Scripts\activate  # Windows
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Create `.env` file
```
GROQ_API_KEY=your_groq_api_key_here
```

### 5. Run
```bash
python manage.py migrate
python manage.py runserver
```

---

## 🔧 Customize for Any Business

Edit `SYSTEM_PROMPT` in `chatbot/views.py`:

```python
SYSTEM_PROMPT = """You are assistant for [Business Name].
Products: [list products]
Pricing: [list pricing]
Contact: [contact info]"""
```

---

## 🔗 Embed on Any Website

```html
<iframe src="https://your-chatbot.onrender.com/"
  width="420" height="620" frameborder="0"
  style="position:fixed; bottom:24px; right:24px;
         border-radius:20px; z-index:9999;">
</iframe>
```

---

## 👩‍💻 Developer

**Bisma Shoukat** — AI Automation Developer

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat-square&logo=linkedin)](https://linkedin.com/in/bisma-shoukat-50ab88378)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?style=flat-square&logo=github)](https://github.com/Bismashoukat)
[![Fiverr](https://img.shields.io/badge/Fiverr-Hire_Me-green?style=flat-square)](https://fiverr.com/bismacoder)

---

## 📄 License

MIT License
