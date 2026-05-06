# redprobe-ai[README.md](https://github.com/user-attachments/files/27426713/README.md)
# 🛡️ RedProbe AI — Adversarial Prompt Testing Dashboard

A full-stack web application for red-teaming AI language models. Built to surface unsafe outputs, jailbreak vulnerabilities, hallucinations, and policy violations before they reach production.

![RedProbe AI Dashboard](https://img.shields.io/badge/Status-Active-brightgreen) ![License](https://img.shields.io/badge/License-MIT-blue) ![AI Safety](https://img.shields.io/badge/Focus-AI%20Safety-red)

---

## 🎯 What It Does

RedProbe AI is a structured adversarial testing environment that allows AI safety analysts to:

- **Design and log** adversarial prompts across 6 threat categories
- **Track model responses** and evaluate them for safety failures
- **Score tests** on a 1–10 risk scale with automatic status classification
- **Visualize threat patterns** through radar charts, bar graphs, and category breakdowns
- **Generate assessment reports** summarizing findings across all test sessions

---

## 🧪 Threat Categories Covered

| Category | Description |
|---|---|
| 🔴 **Jailbreak** | Attempts to override model restrictions via persona injection, compliance priming |
| 🟠 **Bias & Fairness** | Probes for discriminatory or stereotyped outputs |
| 🟣 **Hallucination** | False premise injection, confident misinformation testing |
| 🟡 **Safety Violation** | Hypothetical framing, harmful content elicitation |
| 🔵 **Manipulation** | Flattery, multi-turn social engineering, identity destabilisation |
| 🔴 **Policy Breach** | Prompt leaking, system instruction extraction |

---

## ⚔️ Attack Vectors Supported

- Role-play Injection
- Context Hijacking
- Instruction Override
- Hypothetical Framing
- Token Smuggling
- Prompt Leaking
- Indirect Injection
- Multi-turn Manipulation

---

## 🚀 Getting Started

### Prerequisites
- Node.js 18+
- npm or yarn

### Installation

```bash
git clone https://github.com/Aaronny13/redprobe-ai.git
cd redprobe-ai
npm install
npm run dev
```

Open `http://localhost:5173` in your browser.

---

## 🗂️ Project Structure

```
redprobe-ai/
├── src/
│   ├── App.jsx          # Main application — all views and components
│   ├── data.js          # Seed data, constants, categories, templates
│   └── index.jsx        # React entry point
├── index.html           # HTML shell
├── vite.config.js       # Build config
└── README.md
```

---

## 📊 Features

### Dashboard
Real-time overview of all test sessions with:
- Threat category pie chart
- Model failure rate bar chart
- Attack vector radar map
- Live activity feed

### Test Log
Full searchable, filterable table of all logged tests with:
- Category, severity, and status filtering
- Full prompt + response detail panel
- Analyst notes and risk scoring

### New Test
Structured form for logging new adversarial tests with:
- Pre-built prompt templates for common attack vectors
- Risk score slider (1–10) with auto-status classification
- Model selection and category tagging

### Assessment Report
Auto-generated summary report including:
- Executive summary with key stats
- Flag rate and average risk score
- Complete log of all flagged findings

---

## 🏗️ Tech Stack

- **React 18** — UI framework
- **Recharts** — Data visualisation (radar, bar, pie charts)
- **Vite** — Build tool
- **Vanilla CSS-in-JS** — Zero external UI library dependency

---

## 🔬 Use Cases

- AI safety evaluation and red-teaming
- Pre-deployment model testing
- Training data quality assurance
- Adversarial prompt research
- AI policy and compliance review

---

## 👤 Author

**Aaron Sackitey Teye**  
AI Safety Analyst · Adversarial Prompt Engineer  
[github.com/Aaronny13](https://github.com/Aaronny13)

---

## 📄 License

MIT — free to use, modify, and distribute.
