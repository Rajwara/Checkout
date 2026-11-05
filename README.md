# DRESSUP.GE Checkout — Variant 1 (Single Page)

Static checkout prototype: `index.html`, `style.css`, `script.js`. No build step.

## Deploy on Vercel

1. Go to https://vercel.com/new and import the `rajwara/checkout` GitHub repo.
2. Framework preset: **Other**. Leave build command and output directory empty.
3. Deploy. Every push to the repo redeploys automatically.

## Assets

The page references `../assets/dressup-logo.svg` and `../assets/product-hoodie.svg`.
Served from the site root, those resolve to `/assets/…`, so add an `assets/` folder
at the repo root with those two files.

Demo promo codes: `DRESSUP10` (−10%), `WELCOME20` (−20 ₾).
