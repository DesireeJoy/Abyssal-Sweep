# 🦑 Kraken Sweep

A minesweeper variant themed around a very enthusiastic pup named Kraken. Instead of mines you're avoiding, Kraken is *trying* to find you — but he's a good boy, so getting caught just means he gives you a happy hello with a bunch of tentacles.

[**▶ Play it live**](https://YOUR-USERNAME.github.io/kraken-sweep/)

## How to play

- **Left-click** an unrevealed tile to dig.
- **Right-click** to drop a 🦴 — Kraken loves bones, so this marks where you think he might pop out.
- **Number** = how many adjacent tiles contain a Kraken.
- Reveal every safe tile to win. Click on Kraken and the screen gets consumed by tentacles. He's not eating you, he's just very excited.

## Difficulties

- Calm Waters — 9×9 with 10 Krakens
- Rough Seas — 16×16 with 40 Krakens
- Kraken's Domain — 30×16 with 99 Krakens

## Tech

- Single-file HTML (no build step, no dependencies)
- Canvas + segment-chain physics for the tentacle reveal animation
- CSS animations for click bubbles and bouncing UI

## Run locally

```
git clone https://github.com/YOUR-USERNAME/kraken-sweep.git
cd kraken-sweep
open index.html
```

## Deploy to GitHub Pages

1. Push to GitHub.
2. Go to **Settings → Pages**.
3. Source: **Deploy from a branch**, branch: **main**, folder: **/ (root)**.
4. Save and wait ~1 minute for the URL to go live.
