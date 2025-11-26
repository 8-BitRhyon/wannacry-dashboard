# Project Aghoy: WannaCry Incident Dashboard (8-Bit Edition)

> **A gamified, interactive post-mortem of the 2017 WannaCry Ransomware attack, featuring a simulated AI Incident Commander.**

[![Live Demo](https://img.shields.io/badge/DEMO-LIVE_SITE-success?style=for-the-badge&logo=github)](https://8-bitrhyon.github.io/wannacry-dashboard/)
[![Tech Stack](https://img.shields.io/badge/TECH-HTML5_%7C_Tailwind_%7C_JS-blue?style=for-the-badge)](https://github.com/8-BitRhyon/wannacry-dashboard)

![Dashboard Preview](https://github.com/8-BitRhyon/wannacry-dashboard/blob/main/screenshot.png?raw=true)

---

## Overview

**Project Aghoy** re-imagines the traditional cybersecurity case study as an immersive, 8-bit Incident Command Center.

Instead of reading a static PDF report, users interact with a **Simulated AI Operating System** to uncover tactical failures (EternalBlue), strategic mitigations (The Kill Switch), and operational lessons (Patch Management) from the historic WannaCry outbreak.

---

## Key Features

### Simulated AI Incident Commander
* **No API Keys Required:** Features a custom-built, rule-based Natural Language Processing (NLP) engine that simulates an AI conversation.
* **Context-Aware:** Responds intelligently to specific keywords like `EternalBlue`, `Kill Switch`, `Ransom`, and `NotPetya`.
* **Instant Response:** Zero latency; runs entirely client-side.

### Interactive Forensic Data
* **Executive Brief Generator:** Auto-generates C-Suite summaries of the incident.
* **Live Stat Counters:** Animated visualization of the infection scale (200k+ systems) and financial impact ($4B+).
* **IoC Database:** Tabbed interface displaying File Hashes (SHA-256), Network Indicators, and Ransom Note details.

### "Pixel-Guardian" Design System
* **Retro-Futurism:** Custom CSS implementing CRT scanlines, pixel-perfect fonts (`Press Start 2P`, `VT323`), and neon-terminal aesthetics.
* **Responsive Layout:** Mobile-optimized grid system using Tailwind CSS.
* **Immersive Background:** Parallax scrolling 8-bit city skyline with a procedural digital starfield.

---

## Technical Architecture

This project follows a **Serverless, Client-Side Architecture** for maximum security and performance.

* **Frontend:** Semantic HTML5
* **Styling:** Tailwind CSS (via CDN for portability)
* **Logic:** Vanilla JavaScript (ES6+)
    * **Event-Driven State Management** for chat and modal interfaces.
    * **Asynchronous Simulation** (`async/await`) to mimic network latency and AI "thinking" states.
* **Assets:** Root-relative pathing for seamless deployment on GitHub Pages.

---

## How to Run Locally

No build steps required. This is a "drop-in" deployment.

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/8-BitRhyon/wannacry-dashboard.git](https://github.com/8-BitRhyon/wannacry-dashboard.git)
    ```

2.  **Open the folder**
    ```bash
    cd wannacry-dashboard
    ```

3.  **Launch**
    Open `index.html` in any modern web browser (Chrome, Firefox, Edge).

---

## Knowledge Base (Simulated)

The internal "Brain" `KNOWLEDGE_BASE` object contains curated analysis on:

* **Exploit:** EternalBlue (CVE-2017-0144) / SMBv1 Protocol
* **Actors:** The Shadow Brokers (Leak) / Lazarus Group (Attribution)
* **Defense:** MS17-010 Patch / Network Segmentation

---

## Author

**Rhyon Caleb Foz Santos**
* *Cybersecurity Analyst & Aspiring Full-Stack Developer*
* [LinkedIn](https://www.linkedin.com/in/rhyoncalebfozsantos/) | [GitHub](https://github.com/8-BitRhyon)

---

*Disclaimer: This dashboard is an educational project demonstrating frontend engineering and threat analysis skills. All ransomware data is based on historical public records.*
