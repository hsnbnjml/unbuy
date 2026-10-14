# UNBUY? 🧠

**Opportunity cost, made visible.**

A bilingual (English/العربية) purchase-decision PWA. Every want gets logged,
reframed as hours of your life, scored, and forced to survive a 72-hour
cooling-off period before your budget ever sees it.

**Live app:** https://hsnbnjml.github.io/unbuy/

## How it works

1. **Log a want** — name it, price it.
2. **See the real cost** — price converts to hours of your work; you pick what
   that money could become instead (savings, emergency fund, another goal).
3. **Quick checklist** — realistic use count (cost-per-use), whether you own
   something that does 80% of the job, need vs want, and what happens if you
   just wait 30 days.
4. **Verdict** — a value score (0–100) with Green light / Cool off / Skip it.
5. **72-hour timer** — waiting items count down; when it hits zero you answer
   honestly: still want it, or did the urge fade?
6. **Budget** — remaining monthly budget, money saved by skipping, and waiting
   items ranked by value with fits/doesn't-fit flags.

## Features

- Bilingual UI: English (default) and Arabic with full RTL layout
- Value score computed from cost-per-use, need/want, and duplication
- 72-hour cooling-off queue with live countdowns
- Monthly budget tracking with ranked purchase candidates
- Everything stored locally on your device (localStorage) — no account, no server
- Single-file app: zero dependencies, zero build step

## Install on your phone

**Android:** open the URL in Chrome → ⋮ menu → *Add to Home screen*
**iPhone:** open in Safari → Share → *Add to Home Screen*

## Tech

One self-contained `index.html` — vanilla HTML/CSS/JS, an embedded web app
manifest, and a generated app icon. Deployed via GitHub Pages.

## Roadmap

- [ ] Service worker for offline use
- [ ] Data export/import (backup)
- [ ] Statistics: urge-fade rate over time
- [ ] Custom opportunity goals

## License

MIT
