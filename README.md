# PlayLabs Studio — Intern Handbook

A six-week builder apprenticeship in a single page: find a real problem, build an MVP with AI, ship it, and learn when to keep going or kill it. Designed to be handed to an intern and run alongside a mentor.

**Live site:** https://internship.playlabs.studio/

The handbook is a single self-contained `index.html` — no build step, no dependencies, no framework.

## What's inside

- The **Builder Loop** (9 steps) and a week-by-week six-week plan
- A plain-language explainer of what a **"channel"** (distribution) is and why you pick just one
- The **2026 AI tool stack** with links — ChatGPT + Codex, GitHub, Vercel, Neon, v0, and more
- An interactive **60-second kill check** that scores an idea live (BUILD / CAREFUL / WALK-AWAY)
- A **"validate with commitment before code"** rule and keep-vs-kill criteria
- A pointer to the **PlayLabs Playbook custom GPT** for the keep/wait/kill decision
- **Progress tracking** — checkboxes and the kill check persist in the visitor's own browser (via `localStorage`); nothing is sent to a server
- Deliverables, the daily routine (≤30-min standups 3×/week + reviews), and the rules

## View / edit locally

Open `index.html` in any browser, or serve it:

```bash
python3 -m http.server 8080
```

Then open http://localhost:8080

## Hosting

Served via **GitHub Pages** from the `main` branch (root), with a custom domain set in `CNAME` (`internship.playlabs.studio`). Do not delete the `CNAME` file — it keeps the custom domain mapped. To re-check settings: repo **Settings → Pages**.

## Updating the live site

```bash
git add -A
git commit -m "describe the change"
git push
```

The live site refreshes within about a minute. Hard-refresh (Cmd+Shift+R) if the browser shows a cached version.

## License

Content is licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) — reuse and adapt freely, with attribution. See [`LICENSE`](LICENSE).
