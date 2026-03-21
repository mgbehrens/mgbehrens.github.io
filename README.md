# 📘 Engineering Materials Quiz Pack
### 🔗 mgbehrens.github.io

Welcome to the **Engineering Materials Quiz Pack** — a collection of interactive HTML quizzes designed to support learning in **materials science and engineering**.

---

## 🚀 Overview

This repository contains a wide range of quizzes covering key topics such as:

- 🔩 Mechanical Properties  
- 🔬 Diffusion  
- 🧲 Magnetic Properties  
- 🔥 Heat Treatment (TTT & CCT)  
- ⚙️ Tool Steels  
- 🧪 Corrosion (Basic & Advanced)  
- 📊 Phase Diagrams  
- 🏗️ Concrete & Cement  
- 🧱 Glass  
- 🧴 Polymers & Plastics  
- ⚙️ Material Selection  

Each quiz is built using a reusable **HTML + JavaScript template**, making them easy to deploy, edit, and expand.

---

## 🧠 Features

- ✅ Multiple-choice questions with detailed explanations  
- 🎯 Topic-based quizzes aligned to engineering concepts  
- 🌙 Dark-mode friendly (if enabled in your template)  
- 🎉 Scoring system with instant feedback  
- 🔁 Reusable template for creating new quizzes  
- 💻 Runs locally in any web browser (no setup required)

---

## 🛠️ How to Use

1. 📥 Clone or download the repository  
2. 📂 Open any `.html` quiz file  
3. 🌐 Run it in your browser  
4. 🧪 Start answering questions  

---

## ✏️ Creating a New Quiz

1. Copy an existing quiz file  
2. Replace the `QUESTIONS` array:

```javascript
const QUESTIONS = [
  {
    topic: "Example",
    question: "Your question here?",
    choices: ["A", "B", "C", "D"],
    correctIndex: 0,
    explanation: "Explanation goes here."
  }
];

