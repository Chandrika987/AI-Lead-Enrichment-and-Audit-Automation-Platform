# AI Lead Enrichment & Audit Automation Platform


# Project Overview
--------------------------------

This project is an AI-powered lead enrichment and business audit automation platform 

The platform automates the complete workflow from lead submission to AI-generated business analysis and outreach automation.

When a prospect submits company details through the form, the system:

* Collects lead information
* Scrapes publicly available website content
* Uses AI to generate a personalized business audit
* Generates downloadable PDF reports
* Sends automated email responses
* Logs lead data for CRM-style tracking

The goal was to create a clean, scalable, and practical automation workflow that demonstrates problem-solving ability, engineering decisions, and product thinking.

---
## Live Demo



<p align="center">
  <a href="https://simplifiq-ai-assessment.vercel.app/">
    <img src="https://img.shields.io/badge/Live%20Demo-View%20Project-black?style=for-the-badge&logo=vercel" />
  </a>

  <a href="https://github.com/Chandrika987/Simplifiq-ai-assessment">
    <img src="https://img.shields.io/badge/GitHub-Repository-black?style=for-the-badge&logo=github" />
  </a>
</p>

---

# Features

## Core Workflow

* Lead capture form
* Website scraping using Cheerio
* AI-generated business audits
* Dynamic audit rendering
* Downloadable PDF report generation
* Automated email delivery
* Responsive modern UI
* Live deployment on Vercel

## Automation Features

* Automated AI analysis pipeline
* Email outreach automation
* Structured audit generation
* Multi-step backend workflow

## UI Features

* Glassmorphism-inspired modern interface
* Responsive design
* Loading overlays and feedback states
* Dynamic AI result cards
* Smooth transitions and animations

---

# Tech Stack

| Category | Technologies Used |
|---|---|
| Frontend | Next.js 16, React, TypeScript, Tailwind CSS |
| Backend | Next.js API Routes |
| AI Integration | OpenRouter API, GPT-based AI Models |
| Web Scraping | Axios, Cheerio |
| Email Automation | Resend API |
| PDF Generation | jsPDF |
| Icons & UI | Lucide React |
| Deployment | Vercel |
| Version Control | Git, GitHub |
| Styling | Tailwind CSS, Responsive UI Design |
| APIs Used | OpenRouter API, Resend API |


---

# Architecture

```bash
User Form Submission
        ↓
Website Scraping
        ↓
AI Business Analysis
        ↓
Dynamic Audit Rendering
        ↓
PDF Generation
        ↓
Automated Email Delivery
```

---

# Folder Structure

```bash
src/
 ├── app/
 │    ├── api/
 │    │     └── analyze/
 │    │           └── route.ts
 │    ├── globals.css
 │    ├── layout.tsx
 │    └── page.tsx
 │
 ├── components/
 │    ├── AuditCard.tsx
 │    ├── Hero.tsx
 │    ├── LeadForm.tsx
 │    └── Workflow.tsx
 │
 ├── lib/
 │    ├── ai.ts
 │    ├── scrape.ts
 │    ├── email.ts
 │    └── sheets.ts
```

---

# API Requirements

Create a `.env.local` file in the root directory.

## Required Environment Variables

```env
OPENROUTER_API_KEY=your_openrouter_key
RESEND_API_KEY=your_resend_key
```

## Optional

```env
SHEETDB_API_URL=your_sheetdb_url
```

---

# Setup Instructions

## Clone Repository

```bash
git clone https://github.com/Chandrika987/simplifiq-ai-assessment.git
```

## Navigate Into Project

```bash
cd simplifiq-ai-assessment
```

## Install Dependencies

```bash
npm install
```

## Run Development Server

```bash
npm run dev
```



---

# Engineering Decisions

## Why OpenRouter?

OpenRouter was selected because it provides:

* Simple AI model access
* Stable API workflow
* Fast integration
* Flexible model switching

## Why Next.js?

Next.js allowed:

* Fullstack architecture
* API routes within same project
* Fast deployment workflow
* Strong TypeScript support

## Why jsPDF Instead of Screenshot PDFs?

A structured text-based PDF generation approach was used for:

* Better reliability
* Reduced rendering issues
* Multi-page support
* Cleaner export workflow

---

# Tradeoffs & Assumptions

* Website scraping is limited to publicly available content
* AI output quality depends on scraped website information
* Some websites may block scraping requests
* Lightweight architecture was prioritized due to time constraints
* Email delivery currently uses Resend sandbox sender
* PDF generation prioritizes reliability over visual complexity

---

# Limitations

* No authentication system
* No database persistence
* Limited scraping depth
* No retry queue for failed emails
* AI responses may vary between runs

---

# Future Improvements

* Add database integration
* Add CRM dashboard
* Add authentication
* Add queue-based job processing
* Add advanced AI personalization
* Add analytics dashboard
* Add PDF templates and branding
* Add vector search and embeddings

---

# Screenshots

<img width="1888" height="1020" alt="image" src="https://github.com/user-attachments/assets/9dc13f7c-5df3-47d6-9d30-a33c85eaac81" />

<img width="968" height="569" alt="image" src="https://github.com/user-attachments/assets/80e2332b-f676-4318-b5f5-8fd9901c37b1" />


---


---

