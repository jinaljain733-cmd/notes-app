# 📝 Notes App

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3-7952B3?style=flat&logo=bootstrap&logoColor=white)
![localStorage](https://img.shields.io/badge/localStorage-Persistent-orange?style=flat)
![License](https://img.shields.io/badge/License-MIT-yellow?style=flat)

A dynamic notes app built with HTML, CSS, Bootstrap 5 and JavaScript. Add, edit and delete notes with real-time auto-save using localStorage — your notes persist even after closing the browser. No backend required.

---

## 🌐 Live Demo

**[https://jinaljain733-cmd.github.io/notes-app/](https://jinaljain733-cmd.github.io/notes-app/)**

---

## ✨ Features

- Add new notes with one click
- Edit note title and body directly in the card — `contenteditable`
- Delete any note with the close button
- Auto-saves every time you type — no save button needed
- Notes persist in localStorage — survive browser refresh and close
- Responsive grid layout — notes wrap on all screen sizes
- Bootstrap card UI with shadow

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Page structure |
| Bootstrap 5.3.8 | Card UI, grid, buttons — via jsDelivr CDN |
| JavaScript (ES6+) | DOM manipulation, localStorage, event listeners |

---

## 🧠 JavaScript Concepts Used

- `localStorage.setItem()` / `localStorage.getItem()` — persistent browser storage
- `JSON.stringify()` / `JSON.parse()` — serialise notes to JSON for storage
- `document.createElement()` — dynamically create note elements
- `innerHTML` — inject Bootstrap card HTML into new elements
- `contenteditable="true"` — make title and body directly editable
- `addEventListener('input')` — auto-save on every keystroke
- `addEventListener('click')` — delete note on close button click
- `element.remove()` — delete note from DOM
- `querySelectorAll().forEach()` — loop all notes to save them
- `window.onload` — load saved notes when page opens

---

## 📁 Project Structure

```
notes-app/
├── index.html       # App — HTML + Bootstrap + JS in one file
└── README.md
```

---

## 🚀 Getting Started

```bash
git clone https://github.com/jinaljain733-cmd/notes-app.git
cd notes-app
open index.html
```

No install needed — Bootstrap loads from CDN automatically.

---

## 👤 Author

**Jinal Jain**
- GitHub: [@jinaljain733-cmd](https://github.com/jinaljain733-cmd)
- LinkedIn: [linkedin.com/in/jinal-jain-08b70328b](https://linkedin.com/in/jinal-jain-08b70328b)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

> ⚠️ Please do not reuse or redistribute this project as your own work.