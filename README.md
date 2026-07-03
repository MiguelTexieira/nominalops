# NominalOps™

A satirical, single-page **real-time AI environmental toll dashboard** — a parody of corporate ESG monitoring panels, where every LLM request is supposedly causing planetary catastrophe, displayed with absurd fake precision and total deadpan corporate seriousness.

> ALL SYSTEMS NOMINAL.

## Run it

Open `index.html` in a browser. That's it — no build step, no dependencies, no framework. Double-clicking the file works.

To serve locally (so social/meta tags resolve correctly):

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Features

- A master **tokens consumed** counter seeded from the current time, climbing absurdly fast via `requestAnimationFrame`.
- Every metric (water boiled, polar bears displaced, ice cap remaining, GPU temp = "YES", …) is derived from that one number through made-up constants — internally consistent nonsense.
- A second, per-session counter: *since you opened this tab, YOU personally are responsible for…*
- **Persistent lifetime guilt** via `localStorage` — the dashboard remembers you across visits.
- An escalating-denial status badge that degrades the meaning of "nominal" while staying defiantly green.
- Polished "enterprise doom" aesthetic (IBM Plex Sans/Mono, dark hazard-red UI) — a credible-looking corporate dashboard whose *content* is the joke.
- Interactivity: **Send a Prompt** (spikes everything + WebAudio alarm + screen-shake), **Buy Carbon Offset** (plants one sad ASCII tree, changes nothing), tap/hover methodology tooltips, and a copyable damage scorecard.
- **Denial Mode** — a dedicated serenity screen: everything goes calm sage-green, all figures are withheld for your comfort.
- Mobile-first, fully responsive, and respects `prefers-reduced-motion`.

## Deploying

Static site — drop `index.html`, `og.png`, and `og-square.png` on any static host (Netlify, Cloudflare Pages, GitHub Pages, Vercel).

**Before going live:** replace `https://your-domain.example` in `index.html` (3 occurrences) with your real URL so link previews unfurl correctly.

## Disclaimer

Figures accurate to within ±100%. Full methodology available on request (it is not).
