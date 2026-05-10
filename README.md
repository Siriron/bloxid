# BloxID — Builder Identity Protocol

A manga-style onchain builder identity app deployed on **Base Mainnet**.

## Contract
**Address:** `0x7D2c76502334843e482F4EE5012EC0576aE9760A`  
**Chain:** Base Mainnet (Chain ID: 8453)  
**Explorer:** [Basescan](https://basescan.org/address/0x7D2c76502334843e482F4EE5012EC0576aE9760A)

## Features
- 🧑‍💻 Builder profiles (create + update)
- 🚀 Project registry
- 🏁 Milestone tracking
- 📋 Release history
- 🤝 Collaboration attestations
- ⭐ On-chain reputation score

## Tech Stack
- Pure HTML/CSS/JS — no framework
- MetaMask / window.ethereum for writes
- Direct RPC (Base Mainnet) for reads
- Vercel static hosting

## Structure
```
/public/
  index.html   — Landing page (manga style)
  app.html     — Full dApp
vercel.json    — Vercel config
README.md
```

## Deploy to Vercel

### Via GitHub (recommended)
1. Push this repo to GitHub
2. Go to [vercel.com](https://vercel.com) → New Project
3. Import your repo
4. Framework preset: **Other**
5. Output directory: `public`
6. Deploy

### Via Vercel CLI
```bash
npm i -g vercel
vercel --prod
```

## Local Dev
Open `public/index.html` in your browser. No build step needed.
