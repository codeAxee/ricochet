# Ricochet

**An original one-shot bounce puzzle for the web.** Aim a single shot and let it ricochet off the
walls to smash every target in the room — a bite-sized, skill-expressive trick-shot puzzle you can
play in ten seconds and can't put down.

Built by **Codeaxee** in **Unity 6 (WebGL)**, designed for web/Poki.

---

## Play
This repo contains the built **WebGL** game (Poki-ready). Open `index.html` via any static host, or
run locally:
```
npx serve .    # then open the printed URL
```
(It's a mobile-portrait game — a narrow window or phone frames it best.)

## What it is
- **One shot, big cascade** — charge, aim (with a live bounce-preview), and fire a single ball that
  banks off the walls with deterministic, learnable physics. Clear the room in the fewest shots.
- **Skill + payoff** — combo scoring as one shot chains targets, chain-reaction bombs, and a
  one-shot **PERFECT!** clear as the brag moment.

## Features (this build)
- **16 hand-tuned levels** across 2 worlds, with a difficulty curve
- **Moving targets**, armored (multi-hit) targets, and **chain bombs**
- **Pre-clear telegraph** — targets your shot will hit light up as you aim
- **Combo counter** + score, **star rating** per level (fewest shots = 3★)
- **Main menu + scoreboard** (best score, stars, levels) with local save
- **Daily Challenge** — a seeded puzzle everyone gets, once per day
- **Juice** — ball trail, slow-mo + zoom on the winning hit, screen shake, procedural SFX/music
- **100% procedural art & audio** — no third-party assets; distinct clean-neon look

## Tech / web-readiness
- Unity 6 WebGL, **Poki SDK integrated** (rewarded "+1 shot", interstitial between levels,
  gameplayStart/Stop, gameLoadingFinished)
- **~7.25 MB gzipped** initial download (under Poki's 8 MB guideline) — WASM, high stripping,
  procedural art
- Mouse + touch, 16:9 scaling for desktop and mobile web, `localStorage` save

## About Codeaxee
Small indie developer. Also building casual mobile titles (currently in closed testing on Google
Play). Ricochet is our first title built specifically for web.
