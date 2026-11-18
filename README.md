# Khushi Aggarwal — Portfolio

A static, multi-page portfolio (HTML + CSS + JS, Three.js via CDN). No build step needed.

## Deploy to Vercel (easiest: dashboard)
1. Unzip this folder.
2. Push it to a new GitHub repo (e.g. `portfolio`).
3. Go to https://vercel.com/new, import the repo.
4. Framework Preset: **Other**. Leave Build Command and Output Directory empty. Click **Deploy**.

## Deploy with the Vercel CLI
```
npm i -g vercel
cd khushi-portfolio
vercel          # preview
vercel --prod   # production
```

## Edit content
Everything lives in `index.html`:
- Project stories and experience chapters: the `var P=[...]` and `var E=[...]` arrays near the bottom.
- Live links: add URLs for Real Western Estates, Modiv and Tender Tots in the "Live work" cards (Impact page).
- Colours: CSS variables at the top of `<style>` (`--a`, `--b`, `--gr`).

Pages open via the menu (`#about`, `#projects`, `#journey`, `#impact`, `#contact`).
