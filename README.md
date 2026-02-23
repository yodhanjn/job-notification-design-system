# Job Notification Design System

This repository contains the foundational design system for the Job Notification App — a premium, calm, and intentional UI foundation for a B2C SaaS product.

## Principles

- Calm, intentional, coherent, confident
- No gradients, no glass, no neon, minimal motion

## Included files

- `tokens.css` — color, spacing, typography, and transition tokens
- `base.css` — global resets, typography, and layout utilities
- `components.css` — components: top bar, header, cards, buttons, inputs, footer
- `example.html` — a single-page example demonstrating design tokens and components
- `app.html` — full routing app with shared navigation and placeholder pages (/)

## Included routes

- `/` → Dashboard (home page)
- `/saved` → Saved jobs
- `/digest` → Digest view
- `/settings` → Settings
- `/proof` → Proof checklist
- `/404` → Not found page (automatic)

## Usage

1. Open `example.html` in a browser to preview the system.
2. Include the CSS files in this order: `tokens.css`, then `base.css`, then `components.css`.

## Notes

- Typography uses a serif for headings and a system sans-serif for body; body font-size is 16px and line-height is 1.7.
- Spacing is restricted to the scale: 8px, 16px, 24px, 40px, 64px.
- Color palette is intentionally limited to four variables: background, primary text, accent (deep red), and success (muted green).
- Components are framework-agnostic and can be imported into any frontend stack.

If you need a framework adapter (React/Vue) or token formats (SCSS/JSON), open an issue or request and I can scaffold them.
