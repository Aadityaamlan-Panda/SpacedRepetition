# 🧠 Spaced Repetition – Memory Palace System

A minimal, fast, and intuitive **spaced repetition system** designed for a **Memory Palace–based learning workflow**.

This project helps you track, review, and strengthen concepts using a simple yet powerful scoring mechanism.

---

## 🚀 Live Demo

👉 https://aadityaamlan-panda.github.io/SpacedRepetition/

---

## ✨ Features

* 📚 Preloaded concepts (Chemical Engineering + more)
* 🔍 Search and filter concepts
* 🧠 Memory object mapping (Memory Palace integration)
* 📊 Strength-based spaced repetition
* 🎯 Priority scoring system
* 💾 Local storage persistence
* 📥 Export / Import progress (JSON)
* ⚡ Instant feedback with visual cues

---

## 🧠 Core Idea

Each concept is tracked using:

* **Strength** → how well you remember it
* **Repetitions** → how many times reviewed

### 📌 Priority Formula

```
priority = strength − (repetitions × 0.5)
```

* Lower priority → reviewed sooner
* Higher priority → reviewed later

---

## 🎮 Recall System

| Action    | Effect      |
| --------- | ----------- |
| 🟢 Easy   | +2 Strength |
| 🟡 Medium | +1 Strength |
| 🔴 Tough  | −2 Strength |

This mimics real recall difficulty and adapts your revision schedule.

---

## 🏗️ Tech Stack

* HTML
* CSS (custom UI, no frameworks)
* Vanilla JavaScript
* LocalStorage API

---

## 📁 Project Structure

```
SpacedRepetition/
│── index.html      # Main application
│── README.md       # Project documentation
```

---

## 💡 Use Case

* JEE / UPSC preparation
* Engineering subjects
* Memory Palace learners
* Fast revision cycles

---

## 🔧 How to Use

1. Open the app
2. Click recall buttons (Easy / Medium / Tough)
3. Track priority changes
4. Use filters to focus on weak areas
5. Export progress for backup

---

## 📸 Preview

(Add screenshots here later)

---

## 🧪 Future Improvements

* 🔔 Reminder system
* ☁️ Cloud sync
* 📱 Mobile optimization
* 📊 Analytics dashboard
* 🧠 AI-based scheduling

---

## 👨‍💻 Author

**Aadityaamlan Panda**

---

## 📜 License

MIT License
