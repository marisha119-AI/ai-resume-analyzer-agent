# 🧠 AI Resume Analyzer Agent

> Built with n8n | Groq LLM | llama-3.3-70b-versatile

[![n8n](https://img.shields.io/badge/n8n-Workflow%20Automation-orange)](https://n8n.io)
[![Groq](https://img.shields.io/badge/Groq-LLM-blue)](https://groq.com)
[![Llama](https://img.shields.io/badge/Llama-3.3--70b-purple)](https://groq.com)

---

## 🎯 What It Does

An intelligent AI chatbot that **analyzes your resume** and gives detailed professional feedback instantly!

Just paste your resume text in the chat — the AI will analyze it and give you:
- Overall score out of 10
- Strong points in your resume
- Areas that need improvement
- Missing keywords for AI/Tech jobs
- Specific suggestions to make it better

---

## 🔄 Workflow

```
User pastes resume in Chat
          ↓
Chat Trigger Node (Receives input)
          ↓
AI Agent Node (Processes with system prompt)
          ↓
Groq LLM — llama-3.3-70b-versatile (Analyzes resume)
          ↓
Simple Memory (Remembers conversation)
          ↓
Detailed feedback to user ✅
```

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| n8n | Workflow automation platform |
| Groq API | Fast LLM inference |
| llama-3.3-70b-versatile | AI model for analysis |
| Simple Memory Node | Conversation context |
| Chat Trigger | User interface |

---

## ✨ Features

- Instant resume analysis in seconds
- Score out of 10 with detailed breakdown
- Identifies missing AI/Tech keywords
- Remembers conversation for follow-up questions
- Works with any resume format (just paste the text)
- Free to use with Groq API

---

## 🚀 How to Use

1. Open the chat interface
2. Paste your resume text
3. Ask: "Analyze my resume"
4. Get instant detailed feedback!

### Example Questions You Can Ask
- "Analyze my resume and give a score"
- "What keywords am I missing for AI jobs?"
- "How can I improve my resume for tech roles?"
- "Is my resume good for Agentic AI positions?"

---

## ⚙️ Setup

### Prerequisites
- n8n account (cloud or self-hosted)
- Groq API key — free at [console.groq.com](https://console.groq.com)

### Installation
1. Clone this repository
2. Import `resume-analyzer-workflow.json` into n8n
3. Add your Groq API credentials
4. Click **Publish**
5. Open chat and start analyzing!

---

## 🎨 System Prompt Used

```
You are a professional Resume Analyzer.
When a user shares their resume text, analyze it and provide:
1. Overall score out of 10
2. Strong points
3. Areas to improve
4. Missing keywords for AI/Tech jobs
5. Suggestions to make it better
Be specific and helpful.
```

---

## 👩‍💻 Built By

**Marisha Dwivedi** — Agentic AI Developer
- 🌐 Portfolio: [marishadwivedi.netlify.app](https://marishadwivedi.netlify.app)
- 💼 LinkedIn: [linkedin.com/in/marisha-dwivedi-513269271](https://linkedin.com/in/marisha-dwivedi-513269271)
- 🐙 GitHub: [github.com/marisha119-AI](https://github.com/marisha119-AI)

---

## 🔮 Future Improvements

- PDF/DOCX file upload support
- ATS score checker
- Job description matching
- LinkedIn profile analyzer

---

*Made with passion for AI automation 🤖*
