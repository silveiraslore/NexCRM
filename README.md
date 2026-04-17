# NexCRM

🚀 **NexCRM** is a mini CRM (Customer Relationship Management) system with integrated Artificial Intelligence, built to demonstrate a full workflow of CRUD operations, external API consumption, and AI-powered automation.

The project simulates a client and task management dashboard with intelligent insights generated using the Claude API (Anthropic).

---

## ✨ Features

### 📊 Management (CRUD)
- Create, edit, and delete **clients**
- Full management of **tasks**
- Real-time search functionality
- Filtering by status and priority
- Dynamic sorting options

---

### 🤖 Artificial Intelligence (AI)
Integration with Claude API for:

- 📌 Automatic client summaries
- ⚡ Smart task prioritization
- 📈 Global system analysis (CRM insights)
- 💬 Free-form queries based on system data
- 🌦️ Weather impact analysis on external tasks

---

### 🌦️ External API
- Integration with **Open-Meteo API**
- Real-time weather data display
- Correlation between weather conditions and external tasks

---

### 📊 Dashboard
- Real-time KPIs (clients, active tasks, completed tasks, productivity score)
- Client status distribution chart
- Recent records overview

---

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **AI:** Claude API (Anthropic)
- **External API:** Open-Meteo
- **Backend (optional):** Node.js + Express
- **Deployment:** Vercel

---

## 🚀 Getting Started

### 1. Run locally (without AI)

Simply open:

```bash
main.html
````

---

### 2. Run full version (with AI)

```bash
npm install
node server.js
```

Then access:

```bash
http://localhost:3000
```

---

## 🔐 Environment Variables

Create a `.env` file in the root directory:

```env
ANTHROPIC_API_KEY=your_api_key_here
```

---

## 📁 Project Structure

```bash
nexcrm/
├── main.html
├── server.js
├── package.json
├── package-lock.json
├── .gitignore
└── README.md
```

---

## 🤖 AI Architecture

The AI system works through dynamically generated prompts based on real system data.

Flow:

1. System collects data (clients/tasks)
2. Builds a structured prompt
3. Sends request to Claude API
4. Displays AI-generated insights in the UI

---

## 🔒 Security

* API key is never exposed in the frontend
* All requests are proxied through a backend (Node.js or Vercel Functions)
* `.env` file is excluded from version control

---

## 🎯 Project Goal

This project demonstrates a complete system combining:

* Functional CRUD operations
* External API integration
* Practical AI usage in real applications
* Simple and scalable architecture

---

