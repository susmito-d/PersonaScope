# 🧠 PersonaScope

[![Status](https://img.shields.io/badge/Status-Active-success?style=flat-square)]()
[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)]()
[![License](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)]()
[![Made by](https://img.shields.io/badge/Made%20by-Susmito%20Datta-orange?style=flat-square)]()

> **Discover your inner archetype.** Unveil your Sigma, Alpha, or Beta traits through data-driven analysis.

**PersonaScope** is a lightweight, frontend-only web application designed to analyze user personality traits. By answering 100 targeted multiple-choice questions, users generate a detailed JSON profile embedded with reasoning prompts, ready for advanced AI analysis.

---

## 🔗 Live Demo
Experience the application live:  
🚀 **[Click Here to Open PersonaScope](https://susmito-d.github.io/PersonaScope/)**

---

## 📖 Table of Contents
- [Overview](#overview)
- [How It Works](#how-it-works)
- [Key Features](#key-features)
- [AI Powered Analysis](#ai-powered-analysis-workflow)
- [Project Structure](#project-structure)
- [Future Roadmap](#future-roadmap)
- [Author](#author)

---

## Overview
**🚀 The Concept** PersonaScope simplifies personality testing by removing the need for complex backend servers. It runs entirely in the browser, ensuring user privacy and speed. The core innovation lies in its output: instead of a static score, it generates a **Structured JSON Artifact** containing both the user's responses and a sophisticated prompt for LLMs (like ChatGPT, Gemini, or Claude).

---

## How It Works
**🛠 Step-by-Step Guide**

1.  **Landing Page (`index.html`):**
    * Upon visiting the site, users are greeted with the project instructions.
    * Clicking **"Start Assessment"** initializes the quiz session.

2.  **Assessment Phase (`quiz.html`):**
    * Users answer 100 scenario-based questions.
    * Each question offers three distinct choices (A, B, C).

3.  **Data Export & Analysis:**
    * Upon completion, clicking **Submit** triggers a download of a `.json` file.
    * **The Innovation:** This file contains not just answers, but a **Merged Reasoning Prompt**.
    * Users simply upload/paste this JSON content into any AI model.

---

## Key Features
**✨ Why PersonaScope?**

* **⚡ Lightweight Architecture:** Built with pure HTML5, CSS3, and JavaScript. Zero dependencies.
* **🌍 Universal Compatibility:** Hosted on GitHub Pages; accessible from any device.
* **🔒 Privacy First:** No data is sent to any server. Processing is local.
* **🤖 AI-Ready Output:** Pre-formatted data for Large Language Models.
* **🎨 Clean UI:** Minimalist design focusing on user experience.

---

## AI Powered Analysis Workflow
**🤖 The Unique Selling Point**

1.  Complete the quiz and download the `result.json`.
2.  Open **ChatGPT**, **Gemini**, or **Claude**.
3.  Paste the content of the JSON file.
4.  **Instant Result:** The AI will use the embedded "System Prompt" to analyze your Sigma/Alpha/Beta percentages.

---

## Project Structure
**📂 File Organization**

```bash
PersonaScope/
│
├── index.html       # Landing Page (UI & Instructions)
├── quiz.html        # Main Quiz Logic & Interface
├── style.css        # Styling sheet
├── script.js        # Logic handler
└── README.md        # Documentation
