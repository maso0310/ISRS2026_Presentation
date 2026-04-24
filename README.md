# ISRS 2026 — Speech Training Page

Interactive bilingual training page for the ISRS 2026 oral talk.

## Features

- 17 slides, 80+ sentence pairs split EN / ZH side by side
- Browser-native TTS (Web Speech API) — auto-prefers a male English voice when one is available; falls back to whatever the device has
- Per-sentence **▶ 播放 / ■ 停止** toggle
- **Tap any English word** to hear its pronunciation
- **Tap a Chinese sentence** to hear it read aloud
- Per-slide **▶ 整張逐句播放** (English only)
- Stop anytime with the top red button or **Esc** key
- Voice choice persists across reloads (localStorage)

## Open locally

Just open `index.html` in Chrome or Edge.

## Deploy to GitHub Pages (mobile access)

See `../DEPLOY_TO_GITHUB_PAGES.md` for step-by-step instructions.

## Tips

- Best voices are available in **Microsoft Edge** (Natural neural voices).
- Chrome on desktop uses Google voices; quality varies.
- On **iPhone Safari** you get **Alex** / **Daniel** / **Fred** — quite good.
- On **Android Chrome** you get Google voices — acceptable.
- The Voice dropdown lists all English voices on the device (♂/♀/· tag); switch freely.
