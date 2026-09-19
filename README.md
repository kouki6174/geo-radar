# 📡 GEO Radar – Generative Engine Optimization (GEO) & AI Search Analyzer

> **Audit, monitor, and optimize how LLMs (ChatGPT, Perplexity, Google Gemini) perceive, cite, and rank your website.**

🔗 **Live Tool (Free 1-Click Audit):** https://geo-zenith-nexus.vercel.app/

---

## 🚀 Overview

As user search behavior shifts from traditional Google search to conversational AI assistants, conventional SEO metrics are no longer sufficient. 

**GEO Radar** analyzes web pages, predicts recommendation rankings across major LLMs, and provides exact, copy-pasteable content rewrites to increase AI citation probability.

---

## 📊 Plan & Feature Comparison

| Feature | Guest (Unauthenticated) | Free Plan (Signed In) | Pro Plan ($99/mo) |
| :--- | :--- | :--- | :--- |
| **Spot Analysis (New Analysis)** | 1 Free Audit | 3 Audits / month | **100 Audits / month (Unlimited)** |
| **Supported AI Engines** | ChatGPT | ChatGPT | **ChatGPT, Perplexity, Google Gemini** |
| **Audit History Storage** | Local Storage (Session) | Permanent Account Storage | **Permanent Account Storage** |
| **Tracked Sites (Monitoring)** | ❌ Not available | 1 Site (Manual refresh) | **Up to 10 Sites (Automated Weekly Audits)** |
| **Batch Audit Schedule** | ❌ Not available | ❌ Not available | **Customizable Day & Time Settings** |
| **AI Content Advisor (Chat)** | ❌ Not available | Up to 3 Messages | **Unlimited (40-60 word rewrites & tables)** |
| **Automated Alerts (Webhooks)** | ❌ Not available | ❌ Not available | **Weekly Digests & Drop Alerts (Slack / Discord)** |
| **Report Exporting** | ❌ Not available | ❌ Not available | **1-Click PDF & CSV Export** |

---

## ⚡ Core Feature Details

### 1. Instant AI Search Audit & Multi-Engine Ranking
- Real-time website scraping via Jina Reader.
- Predicts citation rankings (`#1` to `#5` or `Not Cited`) across **ChatGPT**, **Perplexity**, and **Google Gemini** with structural reasoning.

### 2. 4-Pillar GEO Evaluation Methodology (100 pts total)
- **Direct Answer Clarity (25 pts):** Checks if primary answers appear within the first 40–60 words.
- **Information Density (25 pts):** Detects unique statistics, original data, and primary source citations.
- **Semantic Structure (25 pts):** Scans heading hierarchies (H1–H3) and structured schema entities.
- **Authority & E-E-A-T (25 pts):** Evaluates author credibility and brand trust signals.

### 3. Contextual AI Content Advisor
- Reads the full scraped page content.
- Generates exact **40–60 word snippet rewrites** and step-by-step implementation tables ready for direct publishing.
- Persistent conversation history linked to each audit report.

### 4. Continuous Auto-Audits & Real-Time Webhook Alerts
- Background scheduled scans for up to 10 monitored sites.
- Sends weekly digest summaries and emergency rank-drop notifications directly to **Slack and Discord**.

### 5. Multi-Format Reporting
- Executive-ready **PDF export** and raw **CSV export** for agency and client reporting.

---

## 🛠️ Tech Stack

- **Frontend:** React, Vite, TypeScript, Tailwind CSS, shadcn/ui
- **Backend & Database:** Supabase (PostgreSQL, Supabase Auth, Row Level Security)
- **AI & Content Extraction:** Jina Reader (Markdown parsing), OpenRouter (Multi-LLM inference)
- **Billing & Subscriptions:** Stripe Checkout & Customer Portal
- **Hosting & Infrastructure:** Vercel

---

## 🌐 Live Application

Try the free 1-click audit with no signup required:  
👉 **[Launch GEO Radar](https://geo-zenith-nexus.vercel.app/)**
