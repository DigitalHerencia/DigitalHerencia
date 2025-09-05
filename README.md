<div align="center">

# Ivan Roman  
**Full-Stack Developer • Modern Indie Hacker • New Mexico Native**  
*Building enterprise SaaS platforms and cultural tech experiences with Next.js 15, React 19, and entrepreneurial spirit*

---

<!-- Badges -->
<div style="display:flex;justify-content:center;align-items:center;flex-wrap:wrap;gap:12px;margin:2rem 0;">
  
[![Next.js 15](https://img.shields.io/badge/Next.js%2015-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)](https://nextjs.org/)
[![React 19](https://img.shields.io/badge/React%2019-61DAFB?style=for-the-badge&logo=react&logoColor=white)](https://react.dev/)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)

</div>

<div style="display:flex;justify-content:center;align-items:center;flex-wrap:wrap;gap:12px;margin:2rem 0;">

[![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)](https://www.prisma.io/)
[![Clerk](https://img.shields.io/badge/Clerk-0055FF?style=for-the-badge&logo=clerk&logoColor=white)](https://clerk.dev/)
[![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-000000?style=for-the-badge&logo=shadcnui&logoColor=white)](https://ui.shadcn.com/)
[![Vercel](https://img.shields.io/badge/Deployed%20on-Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://vercel.com/)

</div>

</div>

---

## 🌎 About Me
I’m a New Mexico native blending **enterprise-grade engineering** with **cultural storytelling** and **entrepreneurial hustle**.  
My work combines SaaS design, real-world analytics, and creative brand expression—applications that are as useful for businesses as they are authentic to communities.  

- 🏢 **Enterprise:** Multi-tenant SaaS, RBAC/ABAC, compliance & reporting  
- 🎨 **Culture-forward:** Tech that integrates Latino/Hispanic identity, storytelling, and brand  
- 🚀 **Operator mindset:** Build for efficiency, margins, and scale  
- 🤖 **AI & Automation:** Context tooling, LLM workflows, domain-specific automation  

---

## 🛠️ Tech Stack
- **Frontend:** Next.js 15 (App Router, RSC), React 19, Tailwind CSS 4, shadcn/ui, Radix  
- **Backend:** Node.js, React Server Actions, Vercel Edge Functions, Express (legacy)  
- **Data:** PostgreSQL (Neon), Prisma ORM, Redis cache layers, analytics dashboards with Nivo & Recharts  
- **Auth & Security:** Clerk, JWT, ABAC/RBAC, SVIX, rate-limiting with Upstash  
- **Tooling & QA:** Vitest, Playwright, Testing Library, GitHub Actions CI/CD  
- **Architecture:** Modular monorepos, microservices, event-driven actions, domain-driven design  
- **Deployment:** Vercel (frontend/edge), Render (backends), GitHub Pages (static), automated workflows  

---

## 🚀 Featured Projects
> *Where enterprise meets entrepreneurship, and culture meets code.*

### 🚚 FleetFusion — Next-Gen Fleet Management SaaS  
**Repo:** [DigitalHerencia/FleetFusion](https://github.com/DigitalHerencia/FleetFusion)  
**Live Demo:** **https://fleet-fusion.vercel.app**  
- **What it is:** A Transportation Management System (TMS) for small-to-midsize logistics operators.  
- **Features:**  
  - Dispatch board for assigning loads  
  - Driver & vehicle management with compliance docs  
  - IFTA fuel tax reporting module  
  - Billing workflows with audit logs  
  - Role-based access (RBAC/ABAC) for dispatchers, admins, drivers  
- **Architecture:**  
  - Next.js 15 + React 19 client, Prisma ORM on Neon/Postgres  
  - Modular domains: `/features/dispatch`, `/features/billing`, `/features/ifta`  
  - Real-time actions via Clerk-authenticated server actions  
  - Edge deployment via Vercel for speed and scaling  
<p align="center">
  <img src="https://raw.githubusercontent.com/DigitalHerencia/FleetFusion/refs/heads/main/public/09b931e1-ec51-4130-add4-39337908a058.png" alt="FleetFusion Screenshot" width="100%" style="border-radius:12px;margin:1rem 0;">
</p>

---

### 🧠 Codebase Context Utility — LLM-Ready Context Tool  
**Repo:** [DigitalHerencia/CodebaseContextUtility](https://github.com/DigitalHerencia/CodebaseContextUtility)  
**Live Demo:** **https://codebase-context-utility.vercel.app**  
- **What it is:** A developer tool that transforms source repos into structured LLM-ready context.  
- **Features:**  
  - Automatic dependency mapping and module graph  
  - Token estimation for GPT-friendly chunking  
  - JSON + Markdown output for embedding pipelines  
  - Integrates seamlessly into AI coding workflows  
- **Architecture:**  
  - Next.js frontend, Node/TypeScript backend  
  - Static analysis of TS/JS repos  
  - Exportable context for Codex or GPT-powered assistants  
<p align="center">
  <img src="https://raw.githubusercontent.com/DigitalHerencia/CodebaseContextUtility/refs/heads/main/public/Screenshot_4-9-2025_162543_codebase-context-utility.vercel.app.jpeg" alt="CodebaseContextUtility Screenshot" width="100%" style="border-radius:12px;margin:1rem 0;">
</p>

---

### 💰 HustlersCode — Street-Smart Business Analytics  
**Repo:** [DigitalHerencia/HustlersCode](https://github.com/DigitalHerencia/HustlersCode)  
**Live Demo:** **https://hustlerscode.vercel.app**  
- **What it is:** A business intelligence dashboard built for hustlers and small-scale entrepreneurs.  
- **Features:**  
  - POS-lite functionality (sales + cash flow)  
  - Inventory tracking for high-turnover items  
  - Profit margin analytics and hustler-friendly UI  
  - Optimized for quick pivots and real-world testing  
- **Architecture:**  
  - SaaS dashboard template with Clerk auth  
  - Analytics-first, with Prisma + Neon as the backbone  
<p align="center">
  <img src="https://raw.githubusercontent.com/DigitalHerencia/HustlersCode/refs/heads/main/public/Screenshot_4-9-2025_171730_hustlerscode.vercel.app.jpeg" alt="HustlersCode Screenshot" width="100%" style="border-radius:12px;margin:1rem 0;">
</p>

---

### 🔥 SiempreNuevo — Culture-Forward Streetwear  
**Repo:** [DigitalHerencia/SiempreNuevo](https://github.com/DigitalHerencia/SiempreNuevo)  
**Live Demo:** **https://siemprenuevo.vercel.app**  
- **What it is:** A bold streetwear storefront built with Next.js.  
- **Features:**  
  - Clothing catalog with cart + checkout flow  
  - Brand aesthetic inspired by NM women’s culture  
  - Responsive mobile-first design  
- **Architecture:**  
  - Headless Next.js storefront, integrated payment hooks  
  - Shadcn/ui + Tailwind for design system  
<p align="center">
  <img src="https://raw.githubusercontent.com/DigitalHerencia/SiempreNuevo/refs/heads/main/public/Screenshot_4-9-2025_172152_siemprenuevo.vercel.app.jpeg" alt="SiempreNuevo Screenshot" width="100%" style="border-radius:12px;margin:1rem 0;">
</p>

---

### 🗣️ FreeTheHomie — Fundraising Platform  
**Repo:** [DigitalHerencia/FreeTheHomie](https://github.com/DigitalHerencia/FreeTheHomie)  
**Live Demo:** **https://freethehomie.vercel.app**  
- **What it is:** A modern fundraising storefront.  
- **Features:**  
  - T-shirt storefront funding community causes  
  - AI-driven content powered by v0.app to tell the story  
  - Social-share optimized and mobile-friendly  
- **Architecture:**  
  - Next.js SaaS shell with Clerk auth  
  - Integrated Stripe + server actions  
<p align="center">
  <img src="https://raw.githubusercontent.com/DigitalHerencia/FreeTheHomie/refs/heads/main/public/freethehomie.png" alt="FreeTheHomie Screenshot" width="100%" style="border-radius:12px;margin:1rem 0;">
</p>

---

### 📸 PortraitPlanner — AI-Enhanced Photography Session Planning  
**Repo:** [DigitalHerencia/PortraitPlanner](https://github.com/DigitalHerencia/PortraitPlanner)  
**Live Demo:** **https://portraitplanner.vercel.app/**  
- **What it is:** A modern planning tool for photographers and studios to organize sessions, build moodboards, and streamline client communication.  
- **Highlights:**  
  - Session scheduling with editable shot plans and deadlines  
  - Moodboard creation to collect references and inspiration per shoot  
  - Gallery & deliverables view to keep client assets centralized  
  - PWA-ready with offline support for on-site work  
  - Theming (dark/light) with customizable tokens for brand fit  
- **Architecture:**  
  - Next.js 15 + React 19, fully typed components  
  - UI built on Tailwind v4 + shadcn/ui + Radix primitives  
  - Forms via React Hook Form + Zod; state via Context + next-themes  
  - Image handling using **@vercel/blob**; analytics via Recharts  
  - Workbox service worker for precaching & runtime strategies  
- **Why it matters:** Turns creative chaos into a predictable workflow, reducing missed shots and client back-and-forth.  
<p align="center">
  <img src="https://raw.githubusercontent.com/DigitalHerencia/PortraitPlanner/refs/heads/main/public/Screenshot_4-9-2025_225338_portraitplanner.vercel.app.jpeg" alt="PortraitPlanner Screenshot" width="100%" style="border-radius:12px;margin:1rem 0;">
</p>

---

## 🧭 How I Work
- **Discovery → Prototype → Ship:** Tight iteration cycles with measurable milestones.  
- **Design Systems:** Reusable components, accessible patterns, and theme tokens.  
- **Observability:** Structured logs + metrics; dashboards for product & ops.  
- **Security by Default:** Principle of least privilege, secrets hygiene, CI policy checks.  
- **Docs as a Feature:** Clear READMEs, setup scripts, and architectural diagrams.

---

## 🤝 Let’s Build Something
📧 **Contact:** [Open an Issue](https://github.com/DigitalHerencia/DigitalHerencia/issues)  
🔗 **Portfolio:** Explore live demos above  
🌟 **Open to:** Full-time roles, contracting, OSS collaborations, and partnerships  

---

> *“Knowledge is power, but applied knowledge is profit.”*
