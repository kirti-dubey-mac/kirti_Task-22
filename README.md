
## Problem Statement
Build a structured hero landing page for "Project" (a workspace/productivity platform) using Tailwind CSS only, with advanced positioning techniques (sticky, relative, absolute, fixed).

## Sections
-Sticky Navbar — logo "Project" left, nav links (Product, Solutions, Resources, Pricing, Log in) + "Get AI free" CTA right. Uses `sticky`, `top-0`, `z-50`.
- Hero Section — gradient background (light orange to white), centered headline "Write, plan, share. With AI at your side.", description text, two CTA buttons ("Get AI free →", "Request a demo").
- Dashboard Preview — centered image inside a `relative` parent container.
- Floating Cards — 3 cards (Tasks, Project Status, Team Activity) positioned with `absolute`, `z-index`, and shadow utilities around the dashboard image.
- Fixed Chat Widget— bottom-right corner, `fixed`, `bottom-6`, `right-6`, `z-50`.

## Tech Stack
- HTML
- Tailwind CSS — no custom CSS
- No JavaScript required

## Files
- index.html — main page
- style.css — included per submission requirements (no custom rules; Tailwind CDN handles styling)
- script.js — included per submission requirements (no interactivity required for this task)