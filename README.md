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

### `venture.html` — Green Service Build (Facilitator)
A 26-week build plan for a green service line, run through the Gears framework. Six phases, one gear each:

| Phase | Weeks | Recommended gear |
|-------|-------|------------------|
| Choose the wedge | 1–3 | Execution |
| Discovery interviews | 2–6 | Exploration |
| Design and pre-sell the flagship | 6–10 | Execution |
| Deliver the paid pilot | 8–14 | Execution |
| Case study and first DFI conversation | 12–20 | Expansion |
| Go / no-go on the evidence | 20–26 | Stabilisation |

Each phase captures the gear actually chosen, evidence produced, live risks, phase owner and budget owner, and closes on a gate question. Choosing a gear other than the recommended one is flagged in the report. The Week 26 gate scores three tests — are corporates paying, is the margin real, is the programme repeatable — and returns a verdict (Go / Hold / No-go). Exports to PDF, CSV, and a pre-filled email draft.

Defaults are pre-filled for an "ISSB-Ready Finance & Board" programme sold into Kenyan banks and listed PIEs, but the service line and wedge are both editable.

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
