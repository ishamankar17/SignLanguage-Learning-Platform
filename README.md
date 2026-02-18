
# 📚 Mini-Project — Learn & Quiz Web App

## 🧠 Project Summary

This is a **full-stack mini project** that combines:

✔ A **frontend** built with HTML, CSS, and JavaScript
✔ A small **Python backend** (for translation/processing)
✔ Interactive features like quizzes and language learning pages

The goal of this project is to demonstrate web-development basics while building a **user-friendly learning application** with multiple interactive pages.

---

## 📌 What This Project Does

This app lets users:

✔ View informational pages (About Us, Contact, Categories)
✔ Learn basic Indian Sign Language (ISL) vocabulary
✔ Practice via a **quiz interface**
✔ Use a **translator** (via Python script)

This showcases core web development skills: layout design, UI interaction, and basic backend integration.

---

## 📁 Repository Structure

```
Mini-Project/
├── static/                # Static assets (CSS / JS / Images)
├── templates/             # HTML templates for frontend
├── __pycache__/           # Python cache files
├── venv/                  # Python virtual environment (not for GitHub)
├── *.html                 # Web pages (Home, Quiz, Translator, etc.)
├── *.css                  # Styling files
├── *.js                   # JavaScript logic
├── translate.py           # Python script for translation logic
├── requirements.txt       # Python libraries
└── Procfile               # Deployment config (e.g., for Heroku)
```

---

## 🛠️ Built With

| Layer               | Technologies                        |
| ------------------- | ----------------------------------- |
| Frontend            | HTML5, CSS3, JavaScript             |
| Backend             | Python                              |
| Optional Deployment | Procfile (for Heroku / web hosting) |

---

## 🖥️ Features

🟢 **Home & Navigation** – Clean homepage with links to all sections
🟢 **Interactive Quiz** – Tests users on sign language knowledge
🟢 **Translator** – Translates selected terms (via `translate.py`)
🟢 **Learn Pages** – Sign language learning content
🟢 **Contact & About Us** – Informative pages for a complete app flow

---

## 🚀 How to Run (Locally)

### 1. Clone the repository

```sh
git clone https://github.com/ishamankar17/Mini-Project.git
cd Mini-Project
```

### 2. Create & activate Python environment (optional but recommended)

Linux/Mac:

```sh
python3 -m venv venv
source venv/bin/activate
```

Windows (PowerShell):

```ps
python -m venv venv
.\venv\Scripts\Activate
```

### 3. Install dependencies

```sh
pip install -r requirements.txt
```

### 4. Start backend (if any)

```sh
python translate.py
```

### 5. Open frontend

Open any `.html` file (e.g., `index.html`) in your browser to interact with the UI.

---

## 📈 What You’ll Learn

This project demonstrates:

✅ Structuring a web app with multiple pages
✅ Linking frontend logic (JS) with backend Python
✅ Basics of user interactivity (quizzes, learning content)
✅ Styling with CSS
📌 *(Good starter full-stack demonstration for portfolios)*

---

## 💡 Potential Improvements

You could extend this project by:

⭐ Adding a real server (Flask / Django)
⭐ Making the translator use an API/model
⭐ Hosting the app online (using Heroku / Vercel)
⭐ Adding database support for quiz analytics

---

## 👩‍💻 About the Author

**Isha Mankar**
AI & Web Development Enthusiast • Data Science Learner
➡️ GitHub: [https://github.com/ishamankar17](https://github.com/ishamankar17)


