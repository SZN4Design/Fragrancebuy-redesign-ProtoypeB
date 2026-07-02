# FragranceBuy.ca — Prototype B: Trust + Discovery

A single-file homepage prototype for **FragranceBuy.ca**, a Canadian discount fragrance
retailer. This is the **Trust + Discovery** concept — a calmer, education-led homepage for
first-time, skeptical, and gift shoppers. It leads with authenticity and guidance instead of
discounts, answering *“can I trust this, and where do I start?”* before it ever sells on price.

It's a CRO (conversion-rate optimization) prototype, so it ships with built-in A/B annotations
and a metrics panel you can toggle on and off.

## What's inside

- `index.html` — the entire prototype: HTML, CSS, and JavaScript in one file, no build step and
  no dependencies.
- `README.md` — this file.

## View it locally

Open `index.html` in any modern browser. That's it — no server or install required.

Or serve it locally:

```bash
# Python 3
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deploy to GitHub Pages

1. Create a new repository on GitHub (for example, `fragrancebuy-prototype-b`).
2. Add these files to the repository root and push:

   ```bash
   git init
   git add index.html README.md
   git commit -m "Add FragranceBuy Prototype B (Trust + Discovery)"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<your-repo>.git
   git push -u origin main
   ```

3. On GitHub, open **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**.
5. Set the branch to **main** and the folder to **/ (root)**, then **Save**.
6. Wait about a minute. Your prototype goes live at
   `https://<your-username>.github.io/<your-repo>/`.

> Already hosting Prototype A in a repo? Drop this `index.html` into a separate repo, branch, or
> subfolder so the two don't overwrite each other.

## Notes

- **Interactive controls** — use the floating *Prototype B* dock (bottom-right) to toggle the CRO
  **annotations** and the **metrics panel**. A Desktop / Mobile switch frames the page in a phone,
  with a working slide-in menu and the mobile “Shop by Mood” carousel.
- **Product imagery** is hotlinked live from FragranceBuy's CDN, so images appear whenever you're
  online; each one hides gracefully if it can't load.
- **Prices, ratings, and metrics are illustrative** placeholders for the prototype — not live store
  data.
- Everything lives in `index.html`, so it's safe to rename, copy, or drop into an existing site.

## Design notes

- **Palette & logo** match the sister concept (Prototype A): warm espresso + cognac amber with a
  gold-leaf accent, on a soft cream canvas.
- **Type** — Fraunces (display headings), Mulish (body/UI), Bodoni Moda (the FragranceBuy
  wordmark), and Space Mono for small captions. Web fonts load from Google Fonts.
