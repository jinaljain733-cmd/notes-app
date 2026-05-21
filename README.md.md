# 📝 Notes App

A lightweight, browser-based notes application built with pure HTML, Bootstrap, and JavaScript. No backend, no database — just your browser storing your notes forever.

---

## 🖥️ Live Preview

> Open `index.html` directly in any browser — no server needed.

---

## ✨ Features

- ➕ Add unlimited notes with one click
- ✏️ Edit note title and body inline (click to type)
- 🗑️ Delete any note instantly
- 💾 Auto-save to **localStorage** — notes survive page refresh and browser close
- 📱 Responsive grid layout — works on mobile, tablet, and desktop

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| HTML5 | Structure |
| Bootstrap 5.3 | Layout & card styling |
| Vanilla JavaScript | Logic & localStorage |

---

## 📁 Project Structure

```
notes-app/
├── index.html      # Everything in one file (HTML + JS)
├── .gitignore      # Git ignore rules
└── README.md       # This file
```

---

## 🚀 How to Run

**Option 1 — Direct open:**
1. Download or clone this repo
2. Double-click `index.html`
3. Opens in your browser instantly ✅

**Option 2 — VS Code Live Server:**
1. Install the **Live Server** extension in VS Code
2. Right-click `index.html` → **Open with Live Server**
3. Opens at `http://127.0.0.1:5500`

---

## 📖 How It Works

```
Click "Add Note"
      ↓
New card appears with default title & body
      ↓
Click title or body to edit (auto-saves on every keystroke)
      ↓
Click ✕ to delete a note
      ↓
Refresh page → notes are still there (localStorage)
```

---

## 📦 localStorage Structure

Notes are saved in the browser as:

```json
[
  { "title": "My Note", "body": "This is the content" },
  { "title": "Second Note", "body": "More content here" }
]
```

---

## 🙋‍♂️ Author

**Jinal Jain**
- GitHub: [@jinaljain733-cmd](https://github.com/jinaljain733-cmd)

---

## 📄 License

This project is open source and free to use for learning purposes.
