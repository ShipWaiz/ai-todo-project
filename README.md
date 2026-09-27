# ⚡ AI-Powered To-Do Project (`ai-todo-project`)

A full-stack Proof of Concept (PoC) task orchestrator integrating **Google Gemini AI** with minimal coding overhead, intuitive modern UI, and zero-setup deployment.

---

## 📦 Project Architecture & Repositories

This project connects two modular repositories:

1. **Frontend (`fe`)**: [**`sujayk46/ai-todo-fe`**](https://github.com/sujayk46/ai-todo-fe)
   - Built with **React 19 + Vite**
   - Modern dark-mode UI with glassmorphism styling
   - Instant task management, category filters, and priority management
   - **AI Features**:
     - ✨ **Smart Goal Breakdown**: Turns high-level objectives into actionable subtasks.
     - 🧠 **Productivity Coach & Prioritizer**: Identifies your top leverage task and quickest win.
     - ☀️ **AI Daily Briefing**: Morning briefing & motivating action plan.

2. **Backend (`be`)**: [**`sujayk46/ai-todo-be`**](https://github.com/sujayk46/ai-todo-be)
   - Built with **Node.js + Express**
   - Zero-configuration persistent storage (`todos.json`)
   - Official `@google/genai` integration with Gemini 3.8 Flash model
   - Built-in smart heuristic fallback so the app works 100% out of the box even before adding an API key.

---

## 🚀 Quick Start (Run Both With One Command)

### 1. Clone this project with submodules
```bash
git clone --recurse-submodules https://github.com/sujayk46/ai-todo-project.git
cd ai-todo-project
```

### 2. Install All Dependencies
```bash
npm run install:all
```

### 3. Launch Frontend & Backend Concurrently
```bash
npm run dev
```

- **Frontend**: [http://localhost:3000](http://localhost:3000)
- **Backend API**: [http://localhost:5000](http://localhost:5000)

---

## 📋 GitHub Repositories Summary

| Component | Repository Link | Stack | Port |
|---|---|---|---|
| **Parent Project** | [`sujayk46/ai-todo-project`](https://github.com/sujayk46/ai-todo-project) | Orchestrator / Submodules | - |
| **Frontend (FE)** | [`sujayk46/ai-todo-fe`](https://github.com/sujayk46/ai-todo-fe) | React 19, Vite, Lucide | 3000 |
| **Backend (BE)** | [`sujayk46/ai-todo-be`](https://github.com/sujayk46/ai-todo-be) | Node.js, Express, Google GenAI | 5000 |
