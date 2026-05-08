# Taski — AI-First Productivity Manager Case Study

Taski is an AI-first productivity manager focused on conversational task management, proactive workflows, reminders, and automation.

This case study documents the product thinking, architecture, workflows, and technical decisions behind the project. It does not include private production code.

---

## Product summary

Taski was built from a practical frustration: most productivity tools still require the user to manually organize everything.

Traditional task apps often depend on the user to:

- open the app
- create the task
- choose the project
- set dates
- add labels
- define priorities
- remember to check the system later

Taski explores a different model: the user should be able to describe what needs to happen, and the system should help capture, organize, remind, and plan proactively.

The goal is not to create another task list. The goal is to build an AI-first workflow manager.

---

## My role

I built Taski independently as a full-stack AI product.

My responsibilities included:

- product definition
- UX model
- database design
- frontend implementation
- backend/API logic
- conversational task workflows
- Telegram integration
- reminder logic
- recurring task handling
- calendar-aware workflows
- AI workflow design
- deployment
- testing and iteration

---

## Core product idea

Taski is designed around a simple principle:

> Productivity tools should reduce mental load, not create more manual work.

Instead of forcing users to structure everything manually, Taski focuses on conversational input and proactive assistance.

Examples of intended workflows:

- “Remind me tomorrow to call the client.”
- “Plan this task for next week.”
- “Create a recurring reminder every Friday.”
- “Move this to Monday if today is too full.”
- “Show me what I should focus on today.”
- “Capture this from Telegram and organize it.”

---

## Product areas

### Conversational task management

The main interaction model is conversation-first.

Key areas:

- natural language task creation
- AI-assisted prioritization
- task clarification
- task organization
- contextual task updates
- reminder creation
- follow-up suggestions

---

### Telegram integration

Taski includes Telegram-based workflows because productivity often starts outside a dashboard.

The idea is to let users capture tasks quickly without opening the main app.

Key areas:

- Telegram Bot API integration
- quick task capture
- reminder input
- conversational interaction
- external notification flows
- async productivity workflows

---

### Reminders and recurring tasks

Taski is designed to handle more than one-off tasks.

Key areas:

- reminders
- recurring tasks
- scheduled notifications
- time-based logic
- task follow-ups
- proactive prompts

---

### Calendar-aware workflows

Taski explores calendar-aware planning, where tasks are not treated as isolated items.

Key areas:

- planning around existing events
- avoiding overloaded days
- suggesting better timing
- connecting tasks with time availability
- future scheduling logic

---

## AI workflows

Taski uses AI as a core part of the product experience.

AI-related areas include:

- natural language task parsing
- conversational task creation
- task prioritization
- reminder interpretation
- follow-up suggestions
- workflow organization
- proactive planning logic

The goal is not to add AI as decoration. The goal is to make the productivity workflow easier and more natural.

---

## Technical stack

### Frontend

- Next.js
- React
- TypeScript
- Tailwind CSS
- modern dashboard UI patterns

### Backend

- Next.js API/server logic
- Prisma
- PostgreSQL
- Supabase
- server-side workflows

### AI

- OpenAI SDK
- structured AI workflows
- conversational task processing
- natural language interpretation

### Integrations

- Telegram Bot API
- calendar-aware logic
- notification workflows
- automation pipelines

### Product infrastructure

- Vercel
- Supabase Auth
- Supabase Storage
- PostgreSQL
- operational monitoring patterns

---

## Main technical challenge

The main challenge in Taski is not creating a basic task CRUD system.

The hard part is designing a system where tasks can be created, interpreted, scheduled, updated, reminded, and reorganized through multiple inputs and AI-assisted workflows.

This creates challenges around:

- task state
- reminder state
- recurring logic
- user intent
- ambiguous language
- time interpretation
- external message input
- notification reliability
- context preservation
- avoiding over-automation

The product needs to help without becoming unpredictable.

---

## Product constraints

Taski has to balance automation with user control.

Important constraints:

- AI should assist, not silently make risky decisions.
- Users must understand what the system planned.
- Reminder logic needs to be predictable.
- Telegram input needs to map cleanly into structured tasks.
- Recurring tasks must avoid duplicated or missed reminders.
- The product must stay simple enough to use daily.

---

## What this project proves

Taski shows my ability to design and build an AI-first product, not just a normal CRUD app with AI added on top.

It demonstrates:

- AI-first product thinking
- conversational UX
- external integrations
- task and reminder modeling
- proactive workflow design
- full-stack implementation
- automation logic
- product judgment around user control

Taski is especially relevant for roles involving AI workflows, productivity systems, internal tools, automation, and product engineering.

---

## Current status

Taski is in active development.

I do not present it as a mature public business. I present it as a serious AI-first product exploration and technical proof of product thinking, workflow automation, and full-stack execution.

---

## Related links

Portfolio:  
https://rodolfo-giannotti.vercel.app

GitHub profile:  
https://github.com/fenixgx

LinkedIn:  
https://www.linkedin.com/in/rodolfo-giannotti-946261409
