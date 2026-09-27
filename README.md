# Brillance — SaaS Landing Page

A polished marketing **landing page for "Brillance"** — a fictional SaaS
product for effortless custom contract billing ("Smart. Simple. Brilliant.").
Built with Next.js 14 + Tailwind, packed with animated landing sections,
a product dashboard preview, pricing, testimonials, and FAQ.

## What it does

- **Hero section** with headline, CTAs, and product imagery.
- **Interactive feature cards** with auto-rotating progress highlights.
- **Dashboard preview** section showcasing the product UI.
- **Integration section** ("Effortless Integration") with updated variants.
- **Stats band** ("Numbers that speak") — key metrics callouts.
- **Documentation section** — docs/teaser links.
- **Testimonials** carousel/section.
- **FAQ** accordion (`faq-section`).
- **Pricing** tiers section.
- **CTA + footer** sections.
- Sticky header navigation and dark/light theme provider.

## Tech stack

- **Framework:** Next.js 14 (App Router) + React 18 + TypeScript
- **UI:** Tailwind CSS, shadcn-style components, Radix UI primitives,
  `lucide-react` icons
- **Tooling:** ESLint, PostCSS

## Quick start

```bash
npm install
npm run dev     # http://localhost:3000
```

Build / serve production:

```bash
npm run build
npm run start
```

> No environment variables required. This is a static marketing page with
> no backend, no API routes, and no server actions.

## Project structure

```
app/                        # Next.js App Router (layout, page, globals.css)
components/
  hero-section.tsx          # Hero headline + CTAs
  feature-cards.tsx         # Auto-rotating feature highlights
  dashboard-preview.tsx     # Product dashboard mockup
  smart-simple-brilliant.tsx# Brand statement section
  your-work-in-sync.tsx     # Feature: work in sync
  effortless-integration*.tsx # Integration sections
  numbers-that-speak.tsx    # Stats/metrics band
  documentation-section.tsx # Docs teaser
  testimonials-section.tsx  # Customer testimonials
  faq-section.tsx           # FAQ accordion
  pricing-section.tsx       # Pricing tiers
  cta-section.tsx           # Call-to-action
  footer-section.tsx        # Footer
  header.tsx                # Sticky nav header
  theme-provider.tsx        # Theme (dark/light)
lib/utils.ts                # Shared helpers
public/                     # Static assets
next.config.mjs             # `output: 'export'` — ships as a static site
```

## Deployment

Fully static — no server required:

```bash
npm run build   # outputs to ./out
```

Deploy `./out` to any static host (Cloudflare Pages, GitHub Pages,
Netlify, Vercel). Live on Cloudflare Pages (see repo homepage).

---

Built by Girish Lade — https://ladestack.in
