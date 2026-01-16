# ⏱️ Pomodoro Timer (Python GUI)
![Python](https://img.shields.io/badge/Python-3.x-blue)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Challenge](https://img.shields.io/badge/Challenge-90DaysOfCode-orange)

---
# 📌 Overview

The Pomodoro Timer is a Python-based GUI application built using Tkinter that helps manage focused work sessions and breaks using the Pomodoro Technique.

This project was developed as part of my #90DaysOfCode journey to practice event-driven programming, strengthen Python fundamentals, and gain hands-on experience building real desktop applications with Tkinter.

---
# 🚀 Key Features

⏱️ 25-minute work sessions with automated breaks

☕ Short and long break cycle handling

🖥️ Clean and minimal Tkinter GUI

🔁 Automatic session switching (Work / Break)

✅ Visual checkmarks for completed work sessions

🔄 Reset functionality for restarting the timer

---
# 📁 Project Structure
```
pomodoro-timer-tkinter/
│
├── main.py
│   └── Core Pomodoro timer logic and Tkinter GUI
│
├── tomato.png
│   └── Image asset used in the application UI
│
└── README.md
    └── Project documentation
```
---
# 🛠️ Application Workflow

The application starts with a default timer screen.

When the user clicks Start:

A work session begins

The timer counts down in real time

Sessions automatically switch between work and breaks

After each completed work session, a checkmark is displayed.

After four work sessions, a long break is triggered automatically.

The Reset button stops the timer and restores the initial state.

This demonstrates real-world GUI state management and timed event handling.

---
# ▶️ Execution Instructions

1️⃣ Clone the Repository
```
git clone https://github.com/your-username/pomodoro-timer-tkinter.git
cd pomodoro-timer-tkinter
```
2️⃣ Run the Application
```
python main.py
```
---
# ⚠️ Important Notes

Python 3.x is required

Tkinter is included with most Python installations

The tomato.png file must remain in the same directory as main.py

Do not close the window while the timer is running to avoid interruptions

---
# 🧠 Concepts Demonstrated

Tkinter GUI development

Event-driven programming

State management using global variables

Timer scheduling using after()

Mathematical time conversion logic

Clean and readable Python code

---
# 🎯 Project Significance

This project goes beyond basic scripting and introduces time-based GUI logic, a key concept in desktop applications. It demonstrates how Python can be used to build interactive productivity tools while maintaining clean structure and readable logic—skills applicable to automation tools and entry-level software development roles.

---
# 👨‍💻 Author

Faiz Hasan

BCA Final Year — Graphic Era University

🚀 Python Learner | #90DaysOfCode

---
*“Consistency and focus turn small sessions into big progress.”*
