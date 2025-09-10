# 🚀 HirePathAI – AI-Powered Interview Preparation Workflow

> **One workflow, zero stress. Get a personalized interview preparation guide in minutes.**

HirePathAI is an **end-to-end n8n automation** project that leverages **AI, APIs, and workflow orchestration** to prepare job seekers for interviews.  
It transforms a simple form submission into a **personalized PDF guide** containing:

- ✅ **Technical & soft skills** required for the role  
- ✅ **10 tailored interview questions**  
- ✅ **Step-by-step roadmap** to prepare effectively  
- ✅ **Instant delivery via email**  

This project showcases my ability to build **real-world automation solutions** combining **AI, API integration, and workflow engineering** — skills directly applicable to **scalable automation, fintech workflows, and intelligent customer solutions.**

---

## ✨ Features

- **AI Integration**: Uses Google Gemini (PaLM API) for generating role-specific content  
- **Automation**: End-to-end workflow powered by n8n  
- **PDF Generation**: Converts AI-generated HTML into a polished, shareable PDF (via PDF.co API)  
- **Email Delivery**: Sends the final PDF directly to the user’s inbox (via Gmail API)  
- **Scalable & Modular**: Can be extended to job portals, HR tools, or career platforms  

---

## 🛠️ Tech Stack & Tools

- [n8n](https://n8n.io) – Workflow automation  
- [Google Gemini (PaLM API)](https://ai.google) – AI content generation  
- [PDF.co API](https://pdf.co/) – PDF conversion  
- [Gmail API](https://developers.google.com/gmail/api) – Email automation  
- **Languages**: JSON, HTML  
- **Concepts**: Workflow Orchestration, API Integration, AI-driven Automation  

---

## ⚙️ How It Works (Workflow Overview)

1. **Form Submission** → Candidate enters job details (title, description, email)  
2. **AI Processing** → Gemini generates skills, interview questions, and roadmap  
3. **PDF Creation** → HTML response converted into a clean PDF via PDF.co  
4. **Delivery** → Workflow emails the personalized guide to the candidate  

```mermaid
flowchart TD
    A[Form Submission] --> B[Gemini AI Content Generation]
    B --> C[Convert HTML → PDF (PDF.co)]
    C --> D[Email Candidate (Gmail API)]
