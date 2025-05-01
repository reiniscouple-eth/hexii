# HEX II

[![Made with p5.js](https://img.shields.io/badge/Made%20with-p5.js-ff69b4?logo=p5.js)](https://p5js.org/)
[![Deployed on Vercel](https://img.shields.io/badge/Deployed%20on-Vercel-black?logo=vercel)](https://vercel.com/)
[![Built by Reiniscouple](https://img.shields.io/badge/Built%20by-Reiniscouple-blueviolet)](https://github.com/reiniscouple)
[![Blockchain: Base](https://img.shields.io/badge/Blockchain-Base-blue)](https://base.org/)

---

**HEX II** is a generative interactive artwork created with **p5.js**, designed by [Reiniscouple](https://github.com/reiniscouple) and Dreamsbender. It presents a hypnotic visual field of rotating hexagons animated by waves of color, evolving continuously with time.

**It also includes a [Farcaster Frame](https://www.farcaster.xyz/) integration** — allowing collectors to interact with the artwork directly from their Farcaster feed.

---

## Preview

![HEX II Screenshot](https://user-images.githubusercontent.com/0000000/hexii-preview.jpg)

> **Live site:** [hex-ii.vercel.app](https://hex-ii.vercel.app)

---

## Features

- Hexagonal grid dynamically animated using sine waves
- Color palette in HSL space mapped to wave dynamics
- Smooth infinite rotation loop
- Responsive layout for desktop and mobile
- Optimized pixel density for performance
- Interactive footer with links to token trading and charts

---

## Web3 Integration

HEX II is also a tokenized asset on the **Base** blockchain:

- [**Trade the token on Zora**](https://zora.co/coin/base:0x54f2b677f0dc7b9e4cefb9f1b7959357ceae72a2?referrer=0xED88ec5Ae50dC47049ab85BbFEF98d38346daac4)
- [**Track the chart on Dexscreener**](https://dexscreener.com/base/0x2e685368582d26E15f8D6d3c4D0307170dF045a1)

### Farcaster Frame

HEX II includes a minimalistic Farcaster Frame for use in social apps:

```html
<meta property="og:title" content="HEX II" />
<meta property="og:image" content="https://hex-ii.vercel.app/preview.png" />
<meta name="fc:frame" content="vNext" />
<meta name="fc:frame:image" content="https://hex-ii.vercel.app/preview.png" />
<meta name="fc:frame:button:1" content="Trade Token" />
<meta name="fc:frame:button:1:action" content="link" />
<meta name="fc:frame:button:1:target" content="https://zora.co/coin/base:0x54f2b677f0dc7b9e4cefb9f1b7959357ceae72a2" />
