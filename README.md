# When Should I Wake Up?

A mobile-first web app that helps you find the best time to wake up — based on your natural sleep cycles.

## How it works

Sleep happens in 90-minute cycles. Waking up between cycles — rather than in the middle of one — is what makes you feel rested. This app calculates the optimal bedtimes or wake-up times based on that principle, with an optional wind-down buffer factored in.

## Features

- **Two modes**
  - **Wake up at…** — pick a wake-up time, get recommended bedtimes
  - **Sleep at…** — pick a bedtime, get recommended wake-up times
- **Color-coded results**
  - 🟢 5–6 cycles — ideal (7.5–9 hours)
  - 🟡 4 cycles — minimum viable (6 hours)
  - ⚫ 3 cycles — too short (not recommended)
- **Adjustable wind-down time** — set how long it takes you to fall asleep after getting into bed (0–45 min, default 14 min). Only available in "Wake up at…" mode.
- **12/24-hour time format toggle**
- **Copy to clipboard** — tap any result to copy the time instantly
- **Mobile-first** — works on any screen size, no install required

## Usage

Open the live app: **[yourusername.github.io/sleep-app](https://yourusername.github.io/sleep-app)**

Or run it locally by cloning the repo and opening `index.html` in any browser — no dependencies, no build step required.

```bash
git clone https://github.com/yourusername/sleep-app.git
cd sleep-app
open index.html
```

## Versioning

| Version | Description |
|---------|-------------|
| v1.0 | Initial release — two modes, cycle length slider, copy to clipboard |
| v1.1 | Removed cycle length slider, added wind-down time slider, improved result cards with bed time + asleep time, renamed "Sleeping now" to "Sleep at…" |
| v1.1.1 | Fixed iOS Safari layout issues — time picker and wind-down slider rendering, touch target sizing, small screen overflow |
| v1.1.2 | Fixed time format toggle not applying universally to time input fields |
| v1.1.3 | Fixed desktop time picker broken after iOS fix; removed "Asleep by" from "Sleep at…" mode |
| v1.1.4 | Added wind-down time toggle, swapped result card hierarchy (Asleep by as primary), hid get-into-bed time when wind-down is off |
| v1.1.5 | Fixed placeholder time showing when wind-down is off; added wind-down explainer text |
| v1.1.6 | Reverted wind-down explainer copy; fixed toggle alignment inconsistency |
| v1.1.7 | Wind-down copy update; explainer visible in both toggle states |
| v1.1.8 | Hid wind-down in "Sleep at…" mode; updated footer, app name, and subtitle |

## Roadmap

- v1.2 — Save user preferences locally (wind-down time, time format)
- v1.3 — Bahasa Indonesia translation
- v1.4 — Nap mode
- v1.5 — Sleep debt tracker
- v2.0 — PWA support (installable on phone like a native app)

## Built with

- Vanilla HTML, CSS, and JavaScript
- No external dependencies
- Single self-contained `index.html` file

## License

MIT — free to use, modify, and distribute.
