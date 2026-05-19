
# EngFlow

**From AI-curious to AI-fluent — one coding session at a time.**

> 🏆 1st Place — Hackathon: Applications that Encourage AI Adoption

---

## What is EngFlow?

84% of developers already use AI. But 66% spend more time fixing AI-generated code than if they'd written it themselves.

The problem was never access. It's guidance.

EngFlow is a **VS Code extension + web dashboard** that helps software engineers adopt AI effectively, safely, and without changing how they work. It lives inside VS Code — open 8 hours a day — and becomes the invisible colleague that always knows more.

---

## Features

### ⏱ Live Timer
Tracks your manual coding time in real-time and compares it to estimated AI completion speed. Nudges you to switch to AI when you're falling behind — without being intrusive.

### 💡 Smart Prompts
Generates context-aware, project-specific prompts based on what you're working on. Stored as reusable skeletons so they adapt to any codebase — your actual code is never exposed.

### 🔔 Smart Pop-ups
Proactively alerts you when you could write the same code more efficiently, right in the moment you need it.

### 🧭 AI Tool Advisor
Analyzes your current file and recommends the best AI tool for the task at hand — directly from the VS Code status bar.

### 🛡 Code Guardrails
Detects risky patterns as you write or paste code. Categorizes findings by severity (LOW / MEDIUM / HIGH) and offers AI-assisted fixes for high-risk issues.

### 🔐 Security Alerts
Scans for API keys, passwords, and sensitive data before you push. Blocks the commit and explains why.

### 📊 Progress Dashboard
Tracks each engineer's AI adoption journey individually and across the team. Managers get full visibility into adoption rates, time saved, and ROI — with real data.

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| VS Code Extension | TypeScript |
| Frontend Dashboard | React Native + Vite |
| Backend API | Java + Spring Boot |
| Database | H2 (embedded) |

---

## Project Structure

```
EngFlow/
├── engflow-extension/   # VS Code extension (TypeScript)
├── engflow-frontend/    # Web dashboard (React Native)
└── engflow-backend/     # REST API (Java/Spring Boot)
```

---

## Getting Started

### Prerequisites
- Node.js 18+
- Java 17+
- VS Code 1.80+

### Clone the repo

```bash
git clone --recurse-submodules https://github.com/stefanachiorean/EngFlow.git
cd EngFlow
```

### Run the extension

```bash
cd engflow-extension
npm install
npm run compile
# Press F5 in VS Code to launch the Extension Development Host
```

### Run the backend

```bash
cd engflow-backend
./mvnw spring-boot:run
```

### Run the frontend dashboard

```bash
cd engflow-frontend
npm install
npm run dev
```

---

## Why EngFlow?

| Without EngFlow | With EngFlow |
|----------------|--------------|
| Developer uses AI randomly | Guided adoption with context-aware suggestions |
| Prompt quality varies wildly | Reusable smart skeletons per task type |
| Security risks go unnoticed | Real-time alerts before they reach production |
| No visibility on AI usage | Team dashboard with adoption metrics and ROI |

---

## Team

| Name | Role |
|------|------|
| Stefana Chiorean | Full-stack, VS Code Extension & Business Plan |
| Madalina Barboi | Backend & Architecture |
| Georgiana Cracana | Frontend |

---

## Contact

## Contact

🐙 [github.com/stefanachiorean/EngFlow](https://github.com/stefanachiorean/EngFlow)

👥 Team:
- [Stefana Chiorean](https://www.linkedin.com/in/stefana-chiorean-1b2b34339/)
- [Madalina Barboi](https://www.linkedin.com/in/madalina-barboi-465577396/)
- [Georgiana Cracana](https://www.linkedin.com/in/georgiana-cracana-1876593bb/?locale=en)

---

## License

MIT
```
