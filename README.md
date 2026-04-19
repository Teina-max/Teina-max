<h1 align="center">Hi, I'm Teina 👋</h1>

<p align="center">
  <b>Full-Stack TypeScript developer · Automation & AI for SMBs</b><br/>
  <sub>Based in Toulouse, France · Available for remote freelance missions</sub>
</p>

<p align="center">
  <a href="https://img.shields.io/badge/status-available_for_hire-brightgreen"><img alt="Available" src="https://img.shields.io/badge/status-available_for_hire-brightgreen"></a>
  <a href="https://www.linkedin.com/in/teina-automatise"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Teina-0A66C2?logo=linkedin&logoColor=fff"></a>
  <a href="mailto:teinateinauri@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-teinateinauri@gmail.com-d14836?logo=gmail&logoColor=fff"></a>
</p>

---

## 🧭 What I do

I build **systems that run in production — not prototypes.**
Five projects already deployed for real clients: real-time multi-store analytics, AI-powered document intelligence (OCR), membership SaaS with full RBAC, and an autonomous prospecting pipeline running 24/7.

**What I deliver concretely:**

- 🛠 Custom dashboards & internal tools (Next.js + Supabase + RLS)
- 🔁 Business process automation (quotes, follow-ups, ERP/SAP imports) with **n8n**
- 🧠 AI integration into existing workflows — OCR with **Claude Vision**, autonomous agents
- 📊 Data pipelines & ETL (PostgreSQL, Edge Functions, pg_cron)

Every project is version-controlled, tested, documented — and the repos below are public so you can inspect the actual code, not just screenshots.

---

## 🧰 Stack

<p>
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-strict-3178C6?logo=typescript&logoColor=fff">
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-16-000?logo=next.js&logoColor=fff">
  <img alt="React" src="https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=000">
  <img alt="Supabase" src="https://img.shields.io/badge/Supabase-Postgres%20·%20RLS%20·%20Edge-3ECF8E?logo=supabase&logoColor=fff">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-16-4169E1?logo=postgresql&logoColor=fff">
  <img alt="n8n" src="https://img.shields.io/badge/n8n-self--hosted-EA4B71?logo=n8n&logoColor=fff">
  <img alt="Claude" src="https://img.shields.io/badge/Anthropic-Claude_Vision-D97757?logo=anthropic&logoColor=fff">
  <img alt="Bun" src="https://img.shields.io/badge/Bun-runtime-000?logo=bun&logoColor=fff">
  <img alt="Tailwind" src="https://img.shields.io/badge/Tailwind-v4-06B6D4?logo=tailwindcss&logoColor=fff">
  <img alt="Playwright" src="https://img.shields.io/badge/E2E-Playwright-45BA4B?logo=playwright&logoColor=fff">
</p>

| Layer | Tools |
|---|---|
| **Frontend** | Next.js 16 · React 19 · TypeScript · Tailwind v4 · shadcn/ui · TanStack Query/Router |
| **Backend** | Supabase (PostgreSQL · RLS · Edge Functions · Auth · Storage · Realtime) |
| **Automation** | n8n (self-hosted) · webhooks · cron jobs · ETL pipelines |
| **AI** | Claude API · Claude Vision OCR · autonomous agents |
| **Infra** | Docker · Cloudflare Tunnel · VPS (Hetzner) · Vercel · GitHub Actions |
| **Data** | PostgreSQL · pg_cron · Airtable · SAP/ERP imports |

---

## 🚀 Featured Work

> All repos below are **anonymized siblings** of real production systems — safe to fork, read, and inspect.

### 📄 [document-intelligence-platform](https://github.com/Teina-max/document-intelligence-platform)
**OCR → matching → dashboard → email relance pipeline** for a French plasturgie SME (1M€/month of quotes).
Claude Vision reads 20+ fields per PDF (FR/ES, cascaded discounts, footer-only fees), matches commandes to offres through a 9-level fallback, and auto-sends J‑30/15/7/1 relances via Outlook.

`Next.js 16` · `Supabase` · `Claude Vision` · `n8n` · `Playwright`
**~34k LOC · 37 SQL migrations · 5 n8n workflows · 40 E2E tests · RLS on 11/11 tables**

### 🤖 [ai-agent-pipeline](https://github.com/Teina-max/ai-agent-pipeline)
**Autonomous 3-agent B2B prospection pipeline** (Scout → Intel → Writer) running 24/7 with human-in-the-loop approval gates.
Detects leads via Google Places, enriches through 9 Python sub-agents (Sirene, DNS-based email discovery, review sentiment), scores 0-100, generates research-backed cold emails via Claude Haiku, ships through Resend.

`Python 3.10+` · `Claude API` · `Supabase` · `Paperclip orchestration` · `Resend`
**5 agents · ~€75/month all-in · production since April 2026**

### 📊 [ecommerce-analytics-platform](https://github.com/Teina-max/ecommerce-analytics-platform)
**Real-time multi-store analytics** for a 6-store retail chain — in production since October 2025.
Dual-API POS reconciliation, self-healing data pipeline with daily integrity checks, webhook enrichment, Telegram bot alerts, and 22-action analytics engine (rankings, challenges, anomalies).

`Deno 2` · `Supabase Edge Functions` · `PostgreSQL` · `pg_cron` · `n8n`
**14 Edge Functions · 22 analytics actions · 62k+ transactions · 12k+ products · 100/100 data quality score**

### 💪 [gym-membership-saas](https://github.com/Teina-max/gym-membership-saas)
**Custom membership SaaS** — staff + member portals, QR check-in, subscription billing, real-time KPI dashboard.
Replaces notebooks + Excel for a single-site gym: 6 subscription plans, 5 RBAC roles, 44 RLS policies, Playwright E2E coverage.

`React 19` · `TanStack Router` · `Supabase` · `TypeScript` · `Vite`
**15 migrations · 44 RLS policies · 5 roles · mobile-first UX**

### ⚡ [portfolio-n8n](https://github.com/Teina-max/portfolio-n8n) · [Live →](https://portfolio-n8n.vercel.app)
**Portfolio site** showcasing n8n + Supabase automation case studies.
Deployed on Vercel, lightweight, focused on conversion for freelance leads.

---

## 💼 Looking for a dev?

I take freelance missions on:

- **Automation & internal tools** for SMBs (10-50 employees)
- **Supabase / PostgreSQL / RLS** architecture and hardening
- **n8n workflow design** (ETL, CRM sync, multi-API orchestration)
- **Document intelligence / AI integration** (OCR, agents, Claude API)

Based in 🇫🇷 Toulouse (CET) · Remote worldwide · English + French.

📫 **[teinateinauri@gmail.com](mailto:teinateinauri@gmail.com)** · 🔗 **[LinkedIn](https://www.linkedin.com/in/teina-automatise)**

---

<p align="center"><sub>Thanks for stopping by — feel free to open an issue on any repo if you have questions.</sub></p>
