# Creative Nomads — AI Marketing Landing Page (Prototype)

A front-end landing-page concept for **Creative Nomads**, exploring how to present AI-powered marketing and automation services. Built with Lovable and maintained as a React/TypeScript project.

> **Status: UI prototype, not a production customer-acquisition website.** This repository is unrelated to the separate [Boost With AI](https://boostwithai.se/) editorial/automation project, despite its historical repository name.

## What's in the prototype

- Single-page layout with navigation, hero, service overview, about section, testimonials layout, contact form, and footer
- Responsive styling using Tailwind CSS and shadcn/ui components
- React Router entry page and 404 route

## Stack

React 18 · TypeScript · Vite · Tailwind CSS · shadcn/ui · React Router · TanStack Query

## Run locally

Requires a current Node.js/npm installation.

```bash
git clone https://github.com/adamamrullah/ai-powered-boost.git
cd ai-powered-boost
npm ci
npm run dev
```

Other commands: `npm run build`, `npm run preview`, `npm run lint`.

## Important implementation limitations

**Please do not treat the demo content as verified business evidence or implemented production functionality.**

- The contact form currently **simulates** successful submission. It does not send, persist, or notify anyone of inquiries.
- Testimonials and headshots are demonstration content; they are **not authenticated client endorsements**.
- Promotional figures appearing in the UI (such as ROI gains, campaign counts, number of clients, or lead volumes) are **unverified placeholders**.
- Some buttons are presentational and have no connected booking or contact action.
- Service descriptions show proposed offerings, not a verified inventory of launched AI services.

Before any public commercial launch, remove or replace placeholder claims/testimonials, wire and test real call-to-actions, implement privacy-compliant contact handling and spam protections, and validate accessibility/performance.

## Why this is in my portfolio

This project demonstrates the front-end product exploration and iteration side of my work: positioning, service information architecture, responsive marketing UI and prototyping with AI-assisted development tools. It **does not** demonstrate a production AI agent or deployed marketing automation.

## Related work

- [Lovable PRD Generator](https://github.com/adamamrullah/lovable-prd-generator) — an open-format agent skill for scoped, testable PRDs.
- [Boost With AI](https://boostwithai.se/) — a separate AI/marketing content project.

## Attribution

Created with assistance from [Lovable](https://lovable.dev/), with project-level product direction and review by Adam Amrullah. The repository contains prototype code; treat any sample marketing content as illustrative.
