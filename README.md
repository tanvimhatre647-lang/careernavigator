# GoalForge — AI Career Navigator 🚀

> **Where do I go from here?**  
> An AI-powered placement planner, skill gap scanner, path simulator, and adaptive roadmap generator — integrated with **Google Gemini 2.5 Flash API**.

![AI Career Navigator](https://img.shields.io/badge/AI-Gemini%202.5%20Flash-b18cff?style=for-the-badge&logo=google)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Built With](https://img.shields.io/badge/Built%20With-HTML5%20%7C%20Vanilla%20JS%20%7C%20CSS3-5eb1ff?style=for-the-badge)

---

## ✨ Features

- 🤖 **Google Gemini 2.5 Flash API Integration**:
  - Live AI parsing of resumes against any target role or job description.
  - Contextual skill inference (detects unlisted implicit skills like REST APIs from full-stack project context).
  - AI-generated executive recommendations & prioritized skill acquisition order with estimated hours and prerequisites.

- 💬 **Interactive AI Career Advisor Chatbot**:
  - Floating `✨ AI Advisor` widget powered by Gemini 2.5 Flash.
  - Ask real-time questions about interview strategies, DSA priorities, resume formatting, and GATE/CAT preparation.

- 🧭 **Career Path Fit Diagnostic**:
  - Evaluates student/professional background against **Tech Roles**, **GATE Exam**, and **CAT/MBA**.
  - Provides detailed pros (`↑`) and cons (`↓`) for each career strategy.

- 🗺️ **Adaptive Multi-Month Roadmap Generator**:
  - Builds 30-day, 3-month, 6-month, or 9-month customized placement roadmaps.
  - Dynamically balances tasks based on available weekly study hours, target focus area, and preferred learning style (projects, tutorials, docs).

- ⏱️ **Schedule Drift & Consequence Mapping**:
  - Tracks missed study days, schedule buffer loss, and compressed revision windows.
  - Offers active schedule recovery options (e.g., adding 1 hr/day, weekend catch-up, or secondary goal slack shifting).

- 🖨️ **Printable AI Career Report**:
  - Executive summary documenting target goals, skill gaps, readiness score, pace, and consistency streak.

- 🎨 **Modern Sleek Aesthetics**:
  - Built with Vanilla HTML5, CSS3, and JavaScript.
  - Dark/Light mode toggle, glassmorphic panel styling, and zero external framework overhead.

---

## 🛠️ Getting Started

### Option 1: Direct Local Execution
No installation or node server required!
1. Clone or download this repository.
2. Open `index.html` in any modern web browser.

### Option 2: Run via Local Server
```bash
npx http-server .
```
Open `http://localhost:8080` in your browser.

---

## ⚡ Gemini API Configuration

The website comes with Gemini 2.5 Flash API support pre-integrated. 
- You can inspect or update the API Key anytime by clicking the **`⚡ Gemini 2.5 AI`** pill badge in the top navigation bar.
- API Key preferences are stored safely in `localStorage`.

---

## 📁 Repository Structure

```
careernavigator/
├── index.html                # Main application (HTML + CSS + Gemini JS Engine)
├── career-navigator.html     # Mirror entry point
├── README.md                 # Project documentation
└── .gitignore                # Git ignore rules
```

---

## 📜 License

Distributed under the MIT License. Built for students and working professionals aiming for higher readiness.
