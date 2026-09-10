# Deep Cortex Designs — Website

The marketing/business website for **Deep Cortex Designs**, a solo web design and development studio based in the Niagara Region, Ontario, serving small businesses across Canada.

## About

Deep Cortex Designs offers small businesses fast, direct web design and development, built on 30 years of technology consulting experience with Fortune 500 companies across Canada and the USA. This site is the studio's own storefront — services, process, pricing, and contact information.

## Contents

- `index.html` — the complete, self-contained website. All CSS is inlined in the `<head>`; there are no external JS dependencies beyond Google Fonts.

## Running locally

No build step required. Either:

- Open `index.html` directly in a browser, or
- Serve the folder locally, e.g.:

  ```bash
  python3 -m http.server 8000
  ```

  then visit `http://localhost:8000`.

## Deploying

This is a static site, so it can be hosted as-is on any static host — GitHub Pages, Netlify, Vercel, Cloudflare Pages, etc.

**GitHub Pages (quick start):**

1. Push this repo to GitHub.
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`.
4. Save — the site will publish at `https://<your-username>.github.io/<repo-name>/`.

## Editing

The page is a single HTML file with inline styles for portability. Section by section, it includes: navigation, hero, services, process, differentiators, about, service area, offer/CTA, contact, capabilities, FAQ, and footer.
