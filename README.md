# 🌙 Peak Sleep

> Sleep smarter. Wake up better.

Peak Sleep is a sleep cycle calculator that helps you find the best time to go to bed or wake up — so you stop waking up groggy and start waking up refreshed. Built as a single HTML file, no installation required.

## The idea

Most people set an alarm for 7 or 8 hours of sleep and hope for the best. But it's not just about how long you sleep — it's about *when* you wake up within your sleep cycle. Waking up at the end of a 90-minute cycle feels natural. Waking up in the middle of one is what causes that heavy, disoriented feeling that can linger for hours.

Peak Sleep does the math for you.

## How to use it

Open the live app: **[ohaiadit.github.io/sleep-app](https://ohaiadit.github.io/sleep-app)**

Two modes:
- **Wake up at…** — pick a wake-up time, get recommended bedtimes
- **Sleep at…** — pick a bedtime, get recommended wake-up times

Results are color-coded by sleep quality:
- 😴 Peak sleep — 6 cycles · 9 hrs
- 🙂 Good sleep — 5 cycles · 7.5 hrs
- 😐 Light sleep — 4 cycles · 6 hrs
- 🥱 Poor sleep — 3 cycles · 4.5 hrs

## Run it locally

No dependencies, no build step. Just clone and open:

```bash
git clone https://github.com/ohaiadit/sleep-app.git
cd sleep-app
open index.html
```

## Features

- Two sleep planning modes
- Color-coded sleep quality results
- 12/24-hour time format toggle
- EN/ID language toggle (defaults to Bahasa Indonesia)
- 24-hour time format defaults when Bahasa Indonesia is selected
- Copy to clipboard — copies the full result summary
- Collapsible sleep cycle explainer and sleep tips
- First-load onboarding tooltip with reopenable help button
- Add to Home Screen prompt for iOS
- Works offline — fully self-contained, no external dependencies

## Built with

This app was built entirely using [Claude Code](https://claude.ai/code) — Anthropic's agentic coding tool — without writing a single line of code manually. The entire development process, from concept to versioning to copy, was done conversationally.

- Vanilla HTML, CSS, and JavaScript
- No frameworks, no libraries, no build tools
- Single self-contained `index.html` file

## Version history

| Version | Description |
|---------|-------------|
| v1.0 | Initial release — two modes, cycle length slider, copy to clipboard |
| v1.1 | Removed cycle length slider, added wind-down time slider, improved result cards, renamed "Sleeping now" to "Sleep at…", app name and subtitle updated |
| v1.2 | Bug fixes and UX improvements — iOS Safari fix, time format toggle, save user preferences, default times, favicon, sleep hours on cards, copy feedback, social meta tags |
| v1.3 | Onboarding tooltip and help button, sleep cycle explainer, sleep tips, result label and color refresh, Add to Home Screen prompt, app renamed to "When Should I Sleep?" |
| v1.4 | App renamed to "Peak Sleep", new subtitle, Bahasa Indonesia translation, EN/ID toggle, 24hr default for ID, apple touch icon, onboarding copy update, fixed favicon clipping on Windows, friendlier onboarding header and app subtitle |
| v1.5 | Results on demand, mode-aware CTA button (show/hide toggle), sleep cycle explainer and sleep tips visible on load, single divider above collapsibles, collapsible order: About Peak Sleep → What is a sleep cycle? → Sleep tips |
| v1.6 | Set sleep reminder button replaces copy button on result cards, hidden in Sleep at mode, iOS Safari layout fix, onboarding copy overhaul, About Peak Sleep collapsible, CTA toggle button, flat onboarding styling |

## Roadmap

These are ideas, not promises. The roadmap may change based on feedback and priorities.

- v1.5 — Nap mode
- v1.6 — Sleep debt tracker
- v2.0 — PWA support (installable on phone like a native app)

## About

I'm a content marketing manager by day — which means late nights, tight deadlines, and way too many hours staring at reports that could've waited until morning. Peak Sleep started as a personal experiment: what if I actually timed my sleep properly instead of just crashing whenever I finished?

I'm not a developer. This entire app was built conversationally through Claude Code, one iteration at a time. It's a personal project, but if it helps you wake up feeling less like a zombie, that's a win.

— Aditya · [linkedin.com/in/ohaiadit](https://linkedin.com/in/ohaiadit)

## License

MIT — free to use, modify, and distribute.
