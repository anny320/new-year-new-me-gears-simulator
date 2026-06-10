# Reset Gears

> Before you set new goals, choose the right gear.

A product site and interactive reset tool for mid-career professionals who don't need more motivation — just clarity, pace, and alignment.

Live at: **https://anny320.github.io/new-year-new-me-gears-simulator/**

---

## Pages

### `index.html` — Landing Page
The main product site with:
- **Hero** — headline, subheading, CTA to free simulator
- **Problem** — why motivation without alignment fails
- **Solution** — the Reset Gears framework intro
- **Products** — four tiers (Free, 30-Day Core, One-Day Light, Guided Reset)
- **Simulator** — free "Choose Your Next Gear" 5-step interactive tool
- **Closing** — email capture / upsell CTA
- **Footer** — © Wakara Technologies Limited

### `reset.html` — 30-Day Reset Programme
Gated with an email signup (Formspree). After unlocking:
- Downloadable `.ics` calendar with 6 milestone reminders
- 4-week guided reflection journal (Week 1–4 tabs)
- Weekly checkbox questions, gear picker, and open reflections
- Summary table, micro-commitment, and Done List
- All responses saved to `localStorage`

---

## The Five Gears

The framework helps you identify your current operating mode:

| Gear | Mode | Colour |
|------|------|--------|
| 1 | Recovery | Red |
| 2 | Stabilisation | Orange |
| 3 | Exploration | Yellow |
| 4 | Execution | Green |
| 5 | Expansion | Blue |

---

## Tech Stack

- Plain HTML / CSS / JS — no framework, no build step
- Deployed via **GitHub Pages** (root of `main` branch)
- Analytics: **Plausible** + **Google Analytics 4** (`G-1Q3XKY7BSC`)
- Email gate: **Formspree** (`https://formspree.io/f/mdavkrkv`)
- Guided Reset enquiries: `wakaratech@gmail.com`
- Data persistence: `localStorage` (no backend)

---

## Product Tiers

| Tier | Price | Action |
|------|-------|--------|
| Free One-Day Reflection | Free | Scrolls to simulator on index.html |
| 30-Day Core Reset | Paid | Opens reset.html (email gated) |
| One-Day Light Reset | Paid | Scrolls to simulator on index.html |
| Guided Reset | Enquiry | Opens pre-filled email to wakaratech@gmail.com |

---

© 2026 Reset Gears | Wakara Technologies Limited
