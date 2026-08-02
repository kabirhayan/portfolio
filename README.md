# Kabirhayan L — Portfolio

Static single-page site. No build step needed.

## Deploy on Vercel

### Option A — Vercel CLI (fastest)
```bash
npm i -g vercel
cd kabi-portfolio
vercel
```
Follow the prompts (link/create project), then run `vercel --prod` to publish.

### Option B — GitHub + Vercel dashboard
1. Push this folder to a GitHub repo.
2. Go to https://vercel.com/new and import the repo.
3. Framework preset: **Other** (or "Static Site") — no build command, no install command needed.
4. Output directory: leave default (Vercel auto-detects `public/`).
5. Click **Deploy**.

### Option C — Drag and drop
1. Go to https://vercel.com/new
2. Drag the `public` folder in directly.

## Structure
```
kabi-portfolio/
├── public/
│   └── index.html   ← your site
└── vercel.json       ← config (clean URLs)
```
