#  Pomodoro Focus Timer

A clean, minimal focus timer built with pure HTML, CSS, and JavaScript — no frameworks, no dependencies.

---

## 📖 About

The **Pomodoro Focus Timer** is a productivity app based on the Pomodoro Technique — a time management method where you work in focused 25-minute sessions separated by short breaks. After every 4 sessions, you earn a longer break.

This app helps you stay focused, avoid burnout, and track how much deep work you're actually getting done each day.

---

## ✨ Features

- ⏱ **Three modes** — Focus (25 min), Short Break (5 min), Long Break (15 min)
- 🔁 **Auto mode switching** — switches to break after focus, and back again automatically
- 🔵 **Session dots** — visual tracker that fills up every 4 sessions
- 📊 **Live stats** — tracks total sessions, minutes focused, and your daily streak
- 🔔 **Flash notifications** — subtle alerts when each phase ends
- 🪟 **Tab title updates** — see the countdown even when the tab is in the background
- 💻 **Zero dependencies** — pure HTML, CSS, JavaScript. Just open and use.

---

## 🚀 Getting Started

### Option 1 — Open directly
Just download `pomodoro-timer.html` and open it in any browser. That's it.

### Option 2 — Run with Live Server (VS Code)
1. Install the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension in VS Code
2. Open the project folder in VS Code
3. Click **Go Live** in the bottom status bar
4. The app opens at `http://127.0.0.1:5500`

---

## 🎯 How to Use

| Action | What it does |
|---|---|
| Click **Start** | Begins the countdown |
| Click **Pause** | Pauses the timer |
| Click **↺** | Resets the current session |
| Click **→** | Skips to the next phase |
| Switch tabs | Jump between Focus / Short Break / Long Break |

The timer automatically moves to the next phase when time runs out. Every 4 focus sessions triggers a long break.

---

## 🛠 Built With

- **HTML5** — structure
- **CSS3** — styling, CSS variables, transitions
- **JavaScript (ES6)** — timer logic, state management
- **SVG** — animated circular progress ring
- **Google Fonts** — JetBrains Mono

---

## 📁 Project Structure

```
pomodoro-timer/
└── pomodoro-timer.html   # entire app in one file
└── README.md
```

---

## 🌐 Live Demo

> Coming soon — deploy via GitHub Pages

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

Made with ☕ and focus.
