# AI Lead Classifier & CRM Automation — n8n

> End-to-end lead management system powered by LLM + n8n. Captures leads, scores intent with AI, routes to priority pipelines, and triggers personalized outreach — fully automated.

![n8n](https://img.shields.io/badge/n8n-workflow-orange) ![AI](https://img.shields.io/badge/LLM-Groq%2FLlama3-blue) ![CRM](https://img.shields.io/badge/CRM-Google%20Sheets-green)

---

## 📹 Demo

https://github.com/1thai8/ai-lead-classifier-n8n/assets/CrmBin.mp4

---

## 💡 What it does

- Captures incoming leads from any source
- AI scores each lead for urgency and intent using Llama 3 via Groq
- Routes high-intent leads to a **Priority pipeline**, others to **General pipeline**
- Logs every lead to Google Sheets (live CRM)
- Sends personalized outreach email via Gmail automatically
- Fires real-time Telegram alerts for Priority leads

---

## 🏗️ Architecture

```
New Lead (Webhook)
       ↓
AI Qualification (Groq/Llama3)
       ↓
  ┌────┴────┐
Priority   General
  ↓           ↓
Gmail      Gmail
Sheets     Sheets
Telegram
```

---

## 🛠️ Tech Stack

| Layer | Tool |
|---|---|
| Automation | n8n |
| AI / LLM | Llama 3 via Groq |
| CRM | Google Sheets |
| Email | Gmail API |
| Alerts | Telegram Bot |

---

## 🎯 Use Case

Built for businesses that receive high lead volume and need to prioritize follow-up automatically — without manual qualification.

---

## 📦 Related Projects

| Project | Description |
|---|---|
| [bonnie-agent](https://github.com/1thai8/bonnie-agent) | AI receptionist for clinic booking via WhatsApp |
| [ai-lead-capture-system](https://github.com/1thai8/ai-lead-capture-system) | Lead capture pipeline with AI outreach |

---

Built by [Thainá Souza](https://github.com/1thai8) · AutoScale AI
