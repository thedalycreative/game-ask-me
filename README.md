# Ask Me

> A little two-player game of hearts: create a room, share the code, ask sweetly, answer bravely and win IOUs.

**Live demo:** [ask-me-game.vercel.app](https://ask-me-game.vercel.app)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square) ![PeerJS](https://img.shields.io/badge/PeerJS-FF6B8B?style=flat-square) ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square)

## Features

- Create a private room and share a short code; your partner joins from their own phone
- Real-time peer-to-peer play with PeerJS (no backend or accounts)
- Question rounds, rewards and a 'You won an IOU!' moment
- Floating-hearts animation, soft serif type, mobile-first layout

## Tech stack

- Single-file HTML with inline CSS and vanilla JavaScript
- PeerJS 1.5 (WebRTC) for the two-player connection
- Cormorant Garamond + Quicksand
- Hosted on Vercel

## Run it locally

```bash
git clone https://github.com/thedalycreative/ask-me-game.git
cd ask-me-game
npx serve .        # open in two browsers to play
```

## Deployment (Vercel)

Static site, repo root is the output. The Vercel project **ask-me-game** deploys `main` to **https://ask-me-game.vercel.app**. (Previously deployed by CLI as `ask-game`; source recovered from that deployment.)

## Screenshots

![Ask Me demo](docs/screenshots/demo.gif)

<p align="center">
  <img src="docs/screenshots/desktop.jpg" alt="Ask Me lobby" width="560">
  <img src="docs/screenshots/mobile.jpg" alt="On a phone" width="260">
</p>

_Captured from the live site (https://ask-me-game.vercel.app). Regenerate with any headless browser; files live in `docs/screenshots/`._

---

Built by [The Daly Creative](https://www.thedalycreative.com) · Perth, WA
