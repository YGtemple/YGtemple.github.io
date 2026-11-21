# ShotStarter — AI Content Assistant

Single-file AI content assistant for **ShotStart**, a brand for beginner short-video creators and small shop owners (US market).

## Features

- **6 content templates**: 15s script + storyboard / product description / 7-day challenge plan / comment reply pack / hook bank / email nurture sequence
- **Bilingual UI** (中文 / English) — interface language and content language are kept separate; generated content stays in English for the US market
- **Live mode**: bring your own OpenAI-compatible chat-completions endpoint (e.g. Doubao Ark). Your API key is stored only in your browser's localStorage and is never bundled with this file
- **Template Library**: offline fallback with randomized variant banks — every generation differs; always labelled as non-live output
- **Shuffle**: regenerate a noticeably different version (live mode sends anti-repeat hints)
- **Brand visuals**: per-product image sets (white-background shots, scene cards, banners) embedded in results
- **History**: last 10 generations, stored locally
- **Honest by instruction**: prompts forbid invented specs, rankings, certifications and guaranteed results

## Usage

Open `index.html` in any modern browser. For live generation, open **Model Settings**, paste your endpoint, API key and model name, then generate. Without a key, the **Template Library** button works fully offline.

## Files

- `index.html` — the entire app (HTML + CSS + JS, no build step, no external dependencies except image CDN)
