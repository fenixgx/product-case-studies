# Product Case Studies

Technical case studies for AI SaaS products, automation systems, and AI-assisted development workflows.

This repository does **not** contain private product code.  
It exists to document architecture, product decisions, technical trade-offs, and implementation thinking behind the products I have built.

---

## Purpose

Most of my work is private product development, so the code for IAMenu, Taski, and Nexus is not public.

Instead of exposing production code, this repository documents:

- product problems
- architecture decisions
- stack choices
- AI workflows
- database and API thinking
- implementation challenges
- trade-offs
- lessons learned

The goal is to show how I think as an AI full-stack developer and technical founder.

---

## Case studies

### [IAMenu.ai](./iamenu)

AI-powered SaaS product for digital menu management.

**Focus areas:**
- SaaS architecture
- public pages and admin dashboards
- AI workflows
- billing logic
- QR tools
- PDF generation
- analytics
- translations
- product constraints

**Stack:** Next.js, TypeScript, Prisma, PostgreSQL, Supabase, OpenAI, Stripe, Vercel

**Status:** live product, early-stage validation.

---

### [Taski](./taski)

AI-first productivity manager focused on conversational task management and proactive workflows.

**Focus areas:**
- AI-first UX
- conversational task creation
- Telegram integration
- reminders
- recurring tasks
- calendar-aware logic
- proactive workflows

**Stack:** Next.js, TypeScript, Prisma, PostgreSQL, Supabase, OpenAI, Telegram integrations

**Status:** in active development.

---

### [Nexus](./nexus)

Internal MCP-based system for persistent AI development context.

**Focus areas:**
- AI-assisted development workflow
- persistent project memory
- SPEC-driven development
- context recovery
- code intelligence
- implementation notes
- previous decisions and errors

**Status:** internal infrastructure.

---

## Repository structure

```text
product-case-studies/
├── README.md
├── iamenu/
│   └── README.md
├── taski/
│   └── README.md
└── nexus/
    └── README.md
