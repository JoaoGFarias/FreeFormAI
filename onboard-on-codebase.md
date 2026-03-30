I want to onboard on this codebase. My main concerns are to understand the implemented features, the planned features, the architecture, the        
technilogies, and the tests strategy. Firstly, explore deeply the codebase and come up with an onboarding plan, focused on using Claude itself to     
deep dive on each step of the plan. Here are the steps I want in the plan, but edit/add as you see fit for this specific context.
In the plan, each step should be followed by prompt suggestions for deep dive and the key files. If any of these is unnecessary 
(e.g. the codebase doesn't have a frontend, simply inform this and don't try to come up with any diverging information).

Step 1 — Architecture & System Design | Goal: Understand what's being built and why.
Step 2 — Backend Module Structure | Goal: Understand the backend components and where code lives.
Step 3 — Frontend & UI | Goal: Understand the frontend components app.
Step 4 — Integration API Contract | Goal: Understand how the components interact between them and with external components.
Step 5 — Implemented Features Tour | Goal: Know what's actually working today.
Step 6 — Test Approach | Goal: Know the esting approach and what's enforced in CI.
Step 7 — Planned Work & Roadmap | Goal: Know what's next and where you can contribute.
Step 8 — Onboarding Summary | Goal: Summarize all the previous steps
  - Phase A: Domain-Driven Design — the business model explained for anyone who understands the domain on a high-level
  - Phase B: Technical Summary — current architecture , current gaps, and future trajectory .
Step 9 — Developer Cheat Sheet
  - Infrastructure commands (start/stop components, full stack)
  - Backend build, run, test commands (with module-specific variants)
  - Frontend dev, test, E2E commands
  - Postman setup (auth headers, key endpoints with sample payloads)
  - Browser navigation guide (key URLs, what you can do)
Step 10 — Agentic Coding Tools Setup & Usage
  - What's configured: skills, *.md rules, hooks
  - The skill catalog with when to use each
  - How to interact with Agentic Coding Tools for the spec lifecycle (create spec → implement → archive)
  - Anti-patterns: what Agentic Coding Tools will refuse or push back on
