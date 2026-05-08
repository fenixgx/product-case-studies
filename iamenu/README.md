# IAMenu.ai — AI-Powered SaaS Product Case Study

IAMenu.ai is an AI-powered SaaS product for digital menu management.

This case study documents the product thinking, architecture, workflows, and technical decisions behind the project. It does not include private production code.

---

## Product summary

IAMenu.ai was built to solve a real operational problem: many small businesses need a practical way to manage digital menus, public pages, product information, translations, QR access, images, and updates without depending on a developer for every change.

The product is not just a landing page or prototype. It includes public-facing pages, an admin dashboard, database models, AI workflows, billing logic, QR tools, PDF generation, analytics, and deployment.

---

## My role

I built IAMenu.ai independently as a full-stack product.

My responsibilities included:

- product definition
- database design
- frontend implementation
- backend/API logic
- admin dashboard
- public menu views
- AI workflows
- authentication and access logic
- billing/subscription logic
- deployment
- operational tooling
- testing and iteration

---

## Core product areas

### Public experience

The public side of the product focuses on fast access, clear presentation, and mobile usability.

Key areas:

- public menu pages
- category and product display
- QR-based access
- responsive layout
- product descriptions
- images
- translations
- lightweight customer-facing experience

---

### Admin experience

The admin side is where businesses manage their content and configuration.

Key areas:

- dashboard
- menu management
- categories and products
- image handling
- AI-assisted content generation
- PDF generation
- QR tools
- analytics
- configuration workflows
- subscription limits

---

## AI workflows

IAMenu.ai uses AI for practical product workflows, not only for marketing.

AI-related areas include:

- product description generation
- automatic translations
- allergen detection
- food image generation
- menu content processing
- conversational/productivity workflows
- AI-assisted setup flows

The goal is to reduce repetitive operational work and help users create better content faster.

---

## Technical stack

### Frontend

- Next.js
- React
- TypeScript
- Tailwind CSS

### Backend

- Next.js API/server logic
- Prisma
- PostgreSQL
- Supabase

### AI

- OpenAI SDK
- image generation
- structured AI workflows
- AI-assisted content generation

### Product infrastructure

- Stripe
- Vercel
- Supabase Auth
- Supabase Storage
- PDF generation
- QR generation
- analytics

---

## Main technical challenge

One of the hardest parts of IAMenu was building a flexible hierarchical content management system.

The product needed to support:

- categories
- subcategories
- products inside categories
- products inside subcategories
- loose products
- ordering
- admin editing
- public rendering

The challenge was keeping the database model, UI state, ordering logic, and user experience consistent across multiple hierarchy levels.

This required careful thinking around:

- data structure
- reorder behavior
- update operations
- edge cases
- frontend state
- persistence
- public display logic

---

## Product constraints

IAMenu.ai had to work as a real product, not as a demo.

That means the system needed to consider:

- non-technical users
- simple onboarding
- subscription limits
- safe content management
- real public pages
- deployment stability
- production data
- user mistakes
- future extensibility

---

## What this project proves

IAMenu.ai shows my ability to build a full SaaS product end to end:

- database schema
- API logic
- public pages
- admin dashboard
- AI workflows
- billing logic
- deployment
- product UX
- operational thinking

The strongest proof is not one isolated feature. It is the full system working together.

---

## Current status

IAMenu.ai is live and in early-stage validation.

I do not present it as a mature business or proven revenue engine. I present it as a real product that demonstrates full-stack execution, AI workflow integration, SaaS thinking, and product ownership.

---

## Related links

Portfolio:  
https://rodolfo-giannotti.vercel.app

GitHub profile:  
https://github.com/fenixgx

LinkedIn:  
https://www.linkedin.com/in/rodolfo-giannotti-946261409
