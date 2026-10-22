## Roberto Zeppilli

**Frontend developer.** React and TypeScript, 3+ years, Latina / Rome, Italy.
I build interfaces that stay fast under real load, and I own features end to end:
from the Figma file to the production deploy, the database behind them included.

Lately my work splits in two directions that keep feeding each other: shipping
products with Next.js 16 and React 19, and building with coding agents as a real
part of the toolchain (Claude Code, MCP servers, structured LLM output) instead of
as autocomplete.

[robertoz.com](https://robertoz.com) · [calibrodigitale.com](https://calibrodigitale.com) · robertozeppilli@proton.me

---

### What I am building

| Project | What it is | Stack |
|---|---|---|
| **[Verdict](https://release-tracker-drab.vercel.app)** · [repo](https://github.com/RobertoZeppilli/release-tracker) | Tracks releases of a curated catalog of languages and frameworks and turns release notes into structured summaries: breaking changes, migration steps, and an explicit *action required / safe to upgrade* verdict. "Understand before you upgrade." | Next.js App Router, Supabase (Postgres, RLS, Auth), Anthropic SDK, TanStack Query, Zod, Tailwind, shadcn/ui, Vitest + Playwright |
| **[fotosottocasa.com](https://fotosottocasa.com)** | Live photography portfolio. Content lives in MDX compiled by Velite, images in Cloudinary, sync scripts so adding a photo is one command and a push. | Next.js, Velite, Cloudinary, Framer Motion, Tailwind |
| **[@robzepdev/react-resize-sentinel](https://www.npmjs.com/package/@robzepdev/react-resize-sentinel)** | Published npm package: a `ResizeObserver` hook under 1.2 kB, zero dependencies. One singleton observer for the whole app, explicit dimension comparison so a re-render fires only when a size actually changes, `borderBox` measurement. | TypeScript, tsup, Vitest |
| **[Passkey authentication](https://authentication-smoky-psi.vercel.app/)** | Passwordless sign-in built on WebAuthn: credential registration, revocation, and session handling, with the failure paths tested rather than assumed. | Next.js 16, SimpleWebAuthn, Drizzle ORM, Neon Postgres, iron-session, Vitest |

In progress: a scroll-driven 3D product site (React Three Fiber, GSAP ScrollTrigger, Lenis)
and **Calibro Digitale**, the banner I use for custom digital work for small businesses.

---

### How I work

- **The domain gets a vocabulary before it gets code.** Every serious project carries a
  `CONTEXT.md` with the terms the product is allowed to use, so the UI, the database
  and the conversation call the same thing by the same name.
- **Hard-to-reverse decisions get written down.** Short ADRs in `docs/adr/`, with the
  rejected options and the reason. Future me is a different developer.
- **Tests where a mistake would be silent.** Unit and integration with Vitest,
  end-to-end with Playwright, typed dictionaries that refuse an incomplete translation.
- **No templates.** The focus is runtime efficiency, accessible interfaces, and plain
  web standards. Performance is a number I measured, not an adjective.
- **Agents with guardrails.** I keep reusable skills, lint pipelines and plans in the
  repository so an agent works inside the project's rules instead of around them.
- Italian and English, in code and with clients.

---

### Stack

**Core** React 18/19 · TypeScript (strict, always) · Next.js App Router · React Native & Expo · Node.js · PHP & Laravel · PostgreSQL · MongoDB  
**State & data** TanStack Query · Redux Toolkit · Zustand · REST & GraphQL · WebSockets · Zod  
**Styling** Tailwind CSS 3/4 · SASS/SCSS architecture · Figma to production · fluid type scales · Motion / GSAP  
**AI** Claude Code CLI · Anthropic & OpenAI APIs · structured LLM output · MCP servers  
**Machinery** Git with semantic commits · Vite · Vitest & Playwright · npm publishing · Vercel · Supabase

---

### Experience

**Frontend Developer Consultant** · Think Positive, Rome (remote / hybrid) · Mar 2025 – Mar 2026  
Large-scale React application for Sisal (Flutter SEA). Feature work, refactoring of legacy
modules for maintainability and responsive consistency, and the rendering glitches nobody
could reproduce across mobile and desktop browsers. Agile team, standardized Git workflow,
code review, unit tests.

**Frontend Developer Consultant** · Self-employed, Latina (remote) · Nov 2024 – Mar 2025  
Responsive and interactive web applications for several clients, state management with
Redux Toolkit, performance and accessibility work, requirements gathered first-hand.

**Frontend Developer** · Magenio, Cagliari (remote) · Mar 2022 – Nov 2024  
Client-facing development on high-scale Magento 2 enterprise stores: modular store
templates from scratch, multi-layered Figma layouts turned into pixel-accurate accessible
interfaces, Alpine.js state and Tailwind bundles. Restructured Magento's PHP rendering
pipeline around modern frontend architecture and cut LCP by over 25%.

---

### Courses and certifications

- **[Claude Code 101](https://verify.skilljar.com/c/qdp2mx9fnbja)** · Anthropic Academy — explore, plan, code, commit
- **Total TypeScript** · Matt Pocock — advanced types and generics
- **Next.js by Vercel** — App Router and SSR optimization
- **[Getting Started with Cybersecurity](https://www.credly.com/badges/8f9a728c-f394-4f3d-b0b4-7d397ce39239/public_url)** · IBM
- **Full Stack Web Developer Intensive** · Boolean Careers — PHP/MySQL and frontend foundations

---

Open to work. If you want to see how I think about a product before the first commit,
read the `CONTEXT.md` and the ADRs in [release-tracker](https://github.com/RobertoZeppilli/release-tracker).
