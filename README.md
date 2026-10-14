# Anchor ⚓️
**AI-Powered Focus Coach Chrome Extension**
### Check out the [DevPost Page!](https://devpost.com/software/anchor-ewiqn2?_gl=1*1wzqdtd*_gcl_au*MzU1MzY1MTQuMTc5MjAyMDcxMQ..*_ga*NDc3NTc5NjkyLjE3OTIwMjA3MTE.*_ga_0YHJK3Y10M*czE3OTIwMjA3MTEkbzEkZzEkdDE3OTIwMjA4MjUkajgkbDAkaDA.)
Anchor is a proactive AI agent designed for individuals impacted by Attention-Deficit/Hyperactivity Disorder (ADHD). No focus? No shame. Using a mix of screen as well as physical detection, we track your attention spans in a non-intrusive manner, and gently steer you back on tack, anchoring your mind on your actual needs.

## Features

* **Visual Distraction Detection:** Takes snapshots of your active tab and analyzes them using Gemini
* **Context-Aware Nudges:** Uses visual understanding to distinguish between productive and disruptive contents for user.
* **Deep Work Reports:** Generates a summary of your session focus and distractions using Generative AI.
* **Strict Blocking:** Optional, custom keyword-based strict blocking for known distraction sites.
* **Break Management:** Built-in Pomodoro-style break timer.

## Tech Stack

* **Frontend:** Chrome Extension (Manifest V3), React, NextJS
* **Backend:** Node.js + Express
* **AI Inference:** Google Gemini 3.0 Flash and Google gemma-3-27b.
* **Communication:** REST API (Extension ↔️ Local Server)

---

## ⚙️ Prerequisites

Before you begin, ensure you have the following installed:
* [Node.js](https://nodejs.org/) (v16 or higher)
* Google Chrome Browser
* An API Key from [OpenRouter](https://openrouter.ai/)

---

## 📥 Installation

### 1. Clone the Repository
```bash
git clone <your-repo-url>
# For front-end
npm install
# For back-end
cd focus-extension/server
npm install
# MacOS/Linux
echo "OPENROUTER_API_KEY=your_key_here" > .env
# Windows
echo "OPENROUTER_API_KEY=your_key_here" | Out-File -Encoding ascii .env
```
