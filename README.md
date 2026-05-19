# Revyze

The official site for Revyze — an 8-week transformation program.

**Live:** [joinrevyze.com](https://joinrevyze.com)

## Stack

Plain HTML, CSS, and a sprinkle of vanilla JS. No build step. Deployed on Vercel.

## Structure

```
.
├── index.html          # The whole site (single-file)
├── vercel.json         # Vercel config (clean URLs, security headers)
└── README.md
```

## Local preview

Open `index.html` in any browser. That's it.

For a local server:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deployment

Pushes to `main` deploy automatically to Vercel.

1. Connect this repo to a Vercel project
2. Add `joinrevyze.com` as the production domain in Vercel
3. Update DNS to point to Vercel (Vercel will show the exact records)

## TODO before launch

- [ ] Wire the `bookCall()` placeholder in `index.html` to a real Calendly link
- [ ] Add Open Graph image for social shares (1200x630, `og.png` in root)
- [ ] Add favicon (`favicon.svg` and `favicon.ico`)
- [ ] Update "4 of 10 spots taken" copy and progress bar as cohort fills
- [ ] Set up basic analytics (Vercel Analytics or Plausible)

## Brand

- Logo: three-shard mark, inline SVG
- Display font: Fraunces (Google Fonts)
- Body font: Inter Tight
- Mono: DM Mono
- Palette: paper `#F4F1EC`, ink `#0E0E0C`, sienna accent `#B85530`
