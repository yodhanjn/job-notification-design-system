Design System — Job Notification App
=================================

This repository contains the foundational design system for the Job Notification App.

Principles
- Calm, intentional, coherent, confident
- No gradients, no glass, no neon, minimal motion

What’s included
- `tokens.css` — color, spacing, typography, transition tokens
- `base.css` — global resets + typography + layout utilities
- `components.css` — buttons, inputs, cards, top bar, header, panels, footer
- `example.html` — a single-page example showing the page structure and components

Usage
1. Open `example.html` in a browser to preview the system.
2. Include the CSS files in your app: first `tokens.css`, then `base.css`, then `components.css`.

Notes
- Typography uses system-safe fonts (serif fallback for headings). You may replace with paid or licensed fonts later.
- Spacing only uses the scale: 8px, 16px, 24px, 40px, 64px.
- Color palette limited to 4 variables by design.

Design tokens and CSS are intentionally small and framework-agnostic — drop them into any frontend stack.
