# Nexora+ — Creative Digital Agency Website

Official website for **Nexora+**, a Jodhpur-based creative digital agency combining creative thinking, digital technology, AI, and marketing to help brands, businesses, creators, and events build a stronger digital presence.

## Site Pages

| File | Purpose |
|------|---------|
| `index.html` | Main one-page site (hero scroll animation, manifesto, services, work, founders, advantage, process, contact) |
| `why-nexora.html` | "Why Nexora+" detail page |

## Structure

```
├── index.html          # Main page
├── why-nexora.html     # Why Nexora+ page
├── assets/             # Founder photos, project logos
├── frames/             # Hero scroll-animation frames (240 JPGs)
├── server.js           # Optional local static server (Node)
└── vercel.json         # Vercel deployment config
```

## Run Locally

Any static server works, e.g.:

```bash
npx serve .        # or
node server.js     # built-in, port 3000
```

Then open `http://localhost:3000`.

## Deploy to Vercel

1. Push this repo to GitHub (already done — see below).
2. Go to [vercel.com/new](https://vercel.com/new) and **Import** the `Nexora-plus` repository.
3. Framework preset: **Other** (it's a static site — no build step needed).
4. Click **Deploy**. Done.

The included `vercel.json` enables clean URLs and long-term caching for the hero frames.

## Git

```bash
git remote add origin https://github.com/taklakshyaa-bot/Nexora-plus.git
git push -u origin main
```
