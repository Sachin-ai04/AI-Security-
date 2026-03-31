# 🛡️ ATLAS AI Firewall: V3 Hybrid AI Security

![License](https://img.shields.io/badge/License-MIT-blue.svg)
![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![FastAPI](https://img.shields.io/badge/FastAPI-0.100+-00a393.svg)
![Gemini](https://img.shields.io/badge/AI-Google_Gemini_2.5_Flash-orange.svg)

**ATLAS** is an enterprise-grade, "LLM-as-a-Judge" firewall designed to protect core database systems and GenAI applications from advanced prompt injections, data exfiltration, and role-play bypasses. 

Unlike traditional firewalls that rely on static keyword matching, ATLAS uses a dedicated Google Gemini AI model to understand the *linguistic intent* of the user, effectively neutralizing sophisticated, plain-English attacks.

[cite_start]Built for the **H.E.A.T 1.0 Hackathon 2026**[cite: 2].

---

## ✨ Core Features

* **🧠 LLM-as-a-Judge Architecture:** Uses a secondary "Guard AI" to grade the threat level of incoming prompts in real-time before they reach the main system.
* **🎚️ Dynamic Threat Sensitivity:** Administrators can adjust the strictness of the firewall on the fly (from 1 to 10) using a live UI slider, dynamically updating the AI's internal system instructions.
* **🍯 Shadow Honeypot:** Instead of outright blocking medium-risk attackers, ATLAS silently routes them to a decoy AI that generates simulated, fake data (like false database credentials) to waste their time and track their behavior.
* **🛟 Emergency Fallback Engine:** Guarantees 99.99% uptime. If the cloud AI API experiences an outage or hits a rate limit (Error 429), ATLAS instantly fails over to a localized, offline heuristic dictionary to maintain security.
* **📊 Transparent Telemetry:** A fully instrumented React/Vanilla JS dashboard featuring real-time response times, financial blast-radius calculations, attacker DNA profiling, and a mathematical ML risk predictor.

---

## 🛠️ Technology Stack

**Frontend:**
* HTML5 / CSS3
* Vanilla JavaScript
* [cite_start]Chart.js (Real-time data visualization) [cite: 17]

**Backend:**
* [cite_start]Python [cite: 17]
* [cite_start]FastAPI (Asynchronous, stateless routing) [cite: 17]
* Uvicorn (ASGI web server)

**AI Engine:**
* Google Generative AI SDK (`google-generativeai`)
* [cite_start]Model: `gemini-2.5-flash` (Optimized for sub-second latency and JSON-enforced output) [cite: 17]

---

## 🚀 Installation & Setup

Follow these steps to run the ATLAS Firewall locally on your machine.

### 1. Clone the Repository
```bash
git clone [https://github.com/YOUR_USERNAME/AI-Security.git](https://github.com/YOUR_USERNAME/AI-Security.git)
cd AI-Security
