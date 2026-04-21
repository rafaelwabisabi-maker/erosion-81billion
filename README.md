# Erosion — 81 Billion

> Interactive data-art PWA on two connected erosions: **81 billion tons** of topsoil lost globally each year, and **€81 billion** stolen annually from elderly Europeans through digital fraud. Same number. Same invisible crisis. Two surfaces.

**Live:** https://erosione.vercel.app
**Status:** Submitted to Prix Ars Electronica 2026 (evaluation phase)

---

## What it is

A single-file Progressive Web App (vanilla JS, no framework) that translates an invisible ecological and social crisis into a sensory experience. Visitors land on a real-time counter showing topsoil loss accumulating live in tons-per-second. A second layer embeds a Windows XP scam simulation — the same visual language elderly users encounter when they lose €81B/year to digital fraud.

The piece connects two numbers that are usually kept separate:
- **81 billion tons** — topsoil lost globally each year (FAO, 2015 baseline)
- **€81 billion** — annual elder fraud volume across the EU (estimate)

## Why

Art-technology pieces often visualise one crisis at a time. Erosion proposes that ecological erosion and cognitive/financial erosion share mechanics: slow, invisible, statistically staggering, individually banal. The counter hypnotises. The XP simulation grounds the abstraction in a specific harm. The visitor cannot unsee the connection.

## Tech

- Single-file HTML + vanilla JavaScript + CSS — no framework, no build step
- Progressive Web App — installable, offline-capable
- Real-time counter driven by per-second extrapolation from FAO annual figures
- Embedded retro Windows XP scam flow (designed as reference, not as vector)
- Hosted on Vercel (static edge deploy)

## Submissions

- **Prix Ars Electronica 2026** — submitted, in evaluation

## Run locally

```bash
git clone https://github.com/rafaelwabisabi-maker/erosion-81billion
cd erosion-81billion
# Open index.html in any browser — no build, no dependencies
```

## Related work

Part of a broader cycle on elder digital fraud + warm technology:
- [SilberWelt](https://github.com/rafaelwabisabi-maker/silberwelt) — 7-app ecosystem for adults 60+
- [ReadCheck](https://github.com/rafaelwabisabi-maker/readcheck) — Canvas-based accessibility engine (NLnet NGI Zero Commons application)

## Author

**Rafael Garcia Vaz de Lima**
[github.com/rafaelwabisabi-maker](https://github.com/rafaelwabisabi-maker)
rafaelwabisabi@gmail.com · Upper Austria

## License

MIT
