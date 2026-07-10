# Hi, I'm Udhaya 👋
### AI Automation Engineer · Chennai, India

<p align="center">
  <a href="https://badges.n8n.io/9897a185-481e-4415-a7df-ca84e22e8a53#acc.zMYcwPtd">
    <img src="PASTE_THE_BADGE_IMAGE_URL_HERE" alt="n8n Certified Badge" width="180">
  </a>
</p>

Fresh B.Tech graduate in AI & Data Science — I build automation systems that solve real problems. Not just prototypes — I've shipped workflows that handled 3200+ emails without hitting Gmail limits, automated an entire hackathon backend end-to-end, and built AI pipelines that generate and sell stock images passively. I think in systems, not scripts.

---

## 🔧 What I Build

| Domain | What I've shipped |
|---|---|
| 🤖 **AI Agents** | Local RAG agent (private LLM + document retrieval) |
| ⚡ **n8n Automation** | 10+ production workflows across events, content, fraud & outreach |
| 🧠 **LLM Pipelines** | Gemini + OpenAI prompt chains for image metadata, fraud detection |
| 📡 **IoT & Embedded** | Sensor systems using Raspberry Pi & Arduino |
| 📊 **ML & Data** | Models & datasets — actively building |

---

## 🛡️ Engineering Approach

> **Free-tier first.** Every workflow above runs on free API limits.
> I solve rate limits with batched loops, staggered waits, and parallel chains —
> not by throwing money at the problem.

- Error monitoring across all workflows → instant Telegram + Gmail alerts
- Google Sheets as a lightweight ops dashboard (status, logs, deduplication)
- Modular design — workflows are reusable and easy to hand off

## 📌 Currently

- 🔭 Building a **Local RAG Agent** — private LLM + document retrieval, fully offline
- 📐 Planning **AI agent pipelines**, ML models & LLM fine-tuning projects
- 🤝 Open to **AI automation freelance**, internships & collaborations

---

## 🧰 Tech Stack

`n8n` `Python` `LangChain` `Ollama` `Google Gemini` `OpenAI` `HuggingFace`
`Raspberry Pi` `Arduino` `FAISS` `ChromaDB` `Google Workspace APIs` `Telegram Bot API`

---
## 🚀 Notable Projects

### 🎯 TARCIN Hackathon — Full Event Automation *(Freelance · Backend)*
Built the entire backend automation for a company-organized hackathon.
- AI reads payment screenshots → extracts UPI transaction ID, amount, bank name
- Duplicate UPI detection to prevent payment fraud
- Automated email pipeline: welcome → reminder → event day → winner announcement
- Sent to HOD, Principal, company & participants — zero manual effort on event day
- **Stack:** n8n · OpenAI Vision · Gmail · Google Sheets

---

### 📧 Startup Outreach — 3200+ Cold Emails, Zero Bans *(Personal ·  Greendigo)*
Built a rate-limit-aware email system for my startup's data collection survey.
- Engineered send pacing + wait logic to stay within Gmail's daily limits
- Dual-loop system: survey email → 2hr gap → thank you email on response
- Telegram notifications for real-time send status monitoring
- **Stack:** n8n · Gmail · Google Sheets · Telegram

---

### 🖼️ AI Stock Image Pipeline — Passive Income System *(Personal)*
End-to-end automation to generate, enhance, and list AI stock images for sale.
- Bulk prompt engineering via 10 parallel Gemini LLM chains (prompt → 10 variations)
- 15 parallel HuggingFace model calls for bulk image generation
- Gemini Vision auto-generates SEO metadata (title, tags, description) per image
- Rate-limit management: batched loops + timed waits across all free-tier APIs
- **Stack:** n8n · Google Gemini · HuggingFace · Google Drive · Google Sheets

---

### 🕵️ Fraud Detection System *(Hackathon · Team Project · Backend)*
Real-time scam detection tool with Telegram + web inputs.
- Accepts text or image input via Telegram bot or website webhook
- LLM classifies message as SCAM / LEGIT / UNKNOWN with confidence score + reason
- Built the full backend; team handled data collection and frontend
- **Stack:** n8n · OpenAI Vision · Google Gemini · Telegram · Webhook

---

### 🎬 Faceless YouTube Automation *(Personal · Built & Tested)*
Fully automated video creation and upload pipeline — no human in the loop.
- Reads content ideas from sheet → AI generates script & caption
- Calls video generation API → polls status → fetches file → uploads to YouTube
- Error logging + status tracking back to Google Sheets
- **Stack:** n8n · OpenAI · YouTube API · Google Sheets

---

### 🏅 Bulk Certificate Generator *(Freelance · Cifware)*
Auto-generates personalized certificates at scale.
- Copies Google Slides template per participant → replaces name/details → converts to PNG
- Generates unique QR code per certificate, cleans up temp files after
- Status tracking per certificate in Google Sheets
- **Stack:** n8n · Google Slides · Google Drive · QR API


---


*"I don't just automate tasks — I automate outcomes."*
