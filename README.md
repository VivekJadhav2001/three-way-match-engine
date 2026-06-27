---
name: @VivekJadhav2001-coding-skill
description: "GitHub profile skill from @VivekJadhav2001. Use it when the task would benefit from mimicking this developer's repo choices, coding style, and implementation techniques."
---

## What they tend to build

- Full-stack MERN apps with a practical, portfolio-friendly scope: resume builders, finance trackers, blogs, dashboards, and “explorer” style utility apps.
- Products that feel production-minded rather than toy demos: AI-assisted workflows, editable content, PDF export, ATS/resume optimization, and real-world CRUD.
- Apps that combine a polished frontend with a lightweight backend: `frontend/` + `backend/` separation is common in the bigger repos.
- Features aimed at usefulness and speed:
  - AI content generation
  - rich text editing
  - export/download flows
  - dashboards and analytics-style views
  - form-heavy user flows

## Coding patterns to mirror

- Prefer a clean split between app layers:
  - `frontend/src/components`, `pages`, `features`, `utils`, `app`
  - `backend/routes`, server entrypoints, small focused route modules
- Default to React + Vite with modern patterns:
  - React Router for navigation
  - Redux Toolkit for shared state
  - Tailwind CSS for styling
  - small reusable UI pieces instead of large monolith components
- For form-heavy flows, use the same “app product” approach seen in their repos:
  - react-hook-form where useful
  - controlled inputs and explicit validation
  - toast-based feedback for actions
- Handle user-facing complexity explicitly:
  - error boundaries
  - loading states
  - notification toasts
  - export/download helpers
- Keep utility code nearby and readable:
  - constants in separate files
  - API helpers isolated from components
  - feature-specific logic grouped together
- Use straightforward, descriptive naming over abstraction-heavy patterns.

## Product and UI taste

- Strong preference for clean, modern, utility-first interfaces.
- UI work is usually oriented around clarity and productivity:
  - ATS-friendly resume layouts
  - editable content surfaces
  - dashboard-like summaries
  - structured forms and sections
- They appear comfortable with richer UI tooling when it supports the product:
  - TinyMCE for editing
  - React Flow for interactive layouts
  - charting and icons for interface polish
- The overall taste is practical: “make the workflow easier” rather than decorative UI.

## Tech stack clues

- Main stack is JavaScript-first, with some TypeScript projects present.
- Frontend:
  - React
  - Vite
  - React Router DOM
  - Redux Toolkit / React Redux
  - Tailwind CSS
  - React Icons
  - Chakra UI appears in the profile stack
  - Chart.js
- Backend:
  - Node.js
  - Express
  - JWT
  - MongoDB
- Third-party/platform tools seen in the profile and repos:
  - Appwrite
  - Supabase
  - GROQ / LLaMA API
  - AWS
  - Render
  - Vercel
- Common tooling:
  - ESLint
  - PostCSS / Tailwind config
  - npm scripts centered on `dev`, `build`, `lint`, `preview`

## When to inspect repos first

- Before generating code for anything involving:
  - Redux Toolkit store shape
  - routing structure
  - backend route naming
  - Appwrite integration
  - AI API calls
  - PDF export or resume rendering
- Before matching their folder conventions in a new app:
  - their repos vary between simple React apps and split frontend/backend structures
  - inspect `package.json` and root directories first to infer architecture
- Before writing UI for forms, editors, or dashboards:
  - the implementation style is likely feature-specific and component-driven
  - the exact dependencies matter a lot here (`TinyMCE`, `react-hook-form`, `react-router-dom`, PDF libs, etc.)
- Before choosing state management:
  - some repos use Redux Toolkit heavily, but not every repo needs it
  - inspect existing patterns rather than assuming a single canonical setup

## Repo Map

- [VivekJadhav2001/AI_Resume_Builder](https://github.com/VivekJadhav2001/AI_Resume_Builder): AI resume builder (2 stars, JavaScript, topics: express, gemini-api, javascript, nodejs)
- [VivekJadhav2001/Connexa](https://github.com/VivekJadhav2001/Connexa) (0 stars, JavaScript, topics: css, expressjs, filesystem, html)
- [VivekJadhav2001/Match-My-Resume](https://github.com/VivekJadhav2001/Match-My-Resume) (0 stars, JavaScript)
- [VivekJadhav2001/Personal-Finance-Tracker-](https://github.com/VivekJadhav2001/Personal-Finance-Tracker-) (1 stars, JavaScript)
- [VivekJadhav2001/AppWriteBlog](https://github.com/VivekJadhav2001/AppWriteBlog) (1 stars, JavaScript)
- [VivekJadhav2001/FrontEnd-Grocery-App](https://github.com/VivekJadhav2001/FrontEnd-Grocery-App) (0 stars, TypeScript)
- [VivekJadhav2001/Educase-Assignment](https://github.com/VivekJadhav2001/Educase-Assignment) (0 stars, JavaScript)
- [VivekJadhav2001/TypeScript](https://github.com/VivekJadhav2001/TypeScript) (0 stars, TypeScript)
- [VivekJadhav2001/Portfolio-Dashboard](https://github.com/VivekJadhav2001/Portfolio-Dashboard) (0 stars, JavaScript)
- [VivekJadhav2001/Github-Explorer](https://github.com/VivekJadhav2001/Github-Explorer): Live Link for Github Explorer (0 stars, JavaScript, topics: javascript, react, reacticons, reactrouterdom)
- [VivekJadhav2001/zorvyn-finance-dashboard](https://github.com/VivekJadhav2001/zorvyn-finance-dashboard) (0 stars, JavaScript)
- [VivekJadhav2001/three-way-match-engine](https://github.com/VivekJadhav2001/three-way-match-engine) (0 stars, JavaScript)
- [VivekJadhav2001/VivekJadhav2001](https://github.com/VivekJadhav2001/VivekJadhav2001) (0 stars)

## How To Use This Skill

- Reach for this skill when the user asks for Vivek Jadhav's style, when the repo stack matches this person's ecosystem, or when studying their real code would reduce made-up output.
- Pick one or more relevant repositories from the list above based on the current task.
- Clone the most relevant repository or repositories into `/tmp` for temporary inspection.
- Study the implementation details, naming patterns, architecture, UI taste, and tooling choices there.
- Return to the main task and apply the useful patterns you observed instead of copying blindly.
- Treat the upstream repositories as reference material for style and technique, then adapt them to the current codebase responsibly.
