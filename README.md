# ⚔️ Soul Archive — Bilingual Game Guide

A fast, bilingual **Arabic / English** guide website for the mobile game *BLEACH: Soul Resonance* — characters, teams, tier lists and planning tools, all in one place.

> 🔒 **Showcase repository.** The source code is private. Recruiters and companies are welcome to contact me for code access.

🌐 **Live site:** [soul-archive-nine.vercel.app](https://soul-archive-nine.vercel.app) *(community guide — work in progress)*

---

## ✨ Features

- 🧮 **Build Calculator** — pick any of the 38 characters, equip weapon, core and set stamps, and see final stats update instantly (verified against in-game stat screens)
- 🧙 **Character Guide** — 38 characters with rarity, attack type and role, plus search and filters
- 📊 **Tier Lists** — community tier lists side by side with dates, plus a "top tier everywhere" consensus view
- 🎟️ **Stamps database** — 131 set, weapon and core stamps with their effects
- 🛡️ **Team Builder** — 17 suggested teams; pick the characters you own and get alternatives for the ones you don't
- 🗓️ **Upgrade Planner** — set current and target level (up to Lv.100) and see exactly which materials you're missing
- 📅 **Release timeline** — latest characters and an estimate for the next release
- ✅ **Transparent accuracy** — verified numbers are marked, estimates are clearly labeled with ≈
- 🌍 **Fully bilingual** — Arabic and English with language-based routing (`/ar`, `/en`) and real RTL layouts
- 📱 **Responsive & SEO-ready** — mobile-friendly, with sitemap and dynamic Open Graph share images

---

## 🛠️ Tech Stack

| Area | Technology |
|---|---|
| Framework | Next.js (App Router), React |
| Language | TypeScript |
| Styling | Tailwind CSS |
| Validation | Zod |
| Testing | Vitest |
| Database | Supabase (PostgreSQL migrations) |
| Hosting | Vercel (continuous deployment) |

---

## 🧩 What I Focused On

- **Internationalization from day one:** one codebase serving two languages and two text directions, including Arabic plural rules.
- **Data accuracy:** typed and validated game data (Zod), with build calculations checked against real in-game stat screens.
- **Performance:** static generation where possible for instant page loads.
- **Quality:** unit tests for the core i18n logic.

---

## 👤 About Me

**Yahya Alfaifi** — Full Stack Developer based in Riyadh, Saudi Arabia. I built Soul Archive solo, from design to deployment.

- GitHub: [@hoxrt](https://github.com/hoxrt)
- LinkedIn: [yahya-alfaifi](https://www.linkedin.com/in/yahya-alfaifi-a49740385)
- Email: yahya.alfaifi131@gmail.com

---

*Soul Archive is an unofficial fan project and is not affiliated with the game's developers or publishers. All game names and assets belong to their respective owners.*

© 2026 Yahya Alfaifi. All rights reserved.
