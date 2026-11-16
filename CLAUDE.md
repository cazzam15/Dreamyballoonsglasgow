# Dreamy Balloons Glasgow: rules for AI sessions

https://dreamyballoonsglasgow.com is the site for a Glasgow balloon decor business: personalised and birthday balloons, garlands, arches and LED light-up letters. Static HTML on GitHub Pages from `main`; no build step.

## Never break

- **Pushing to `main` is live** in about a minute. Work on a branch and open a pull request; Caroline merges.
- **Prices come only from the owner's latest menu PDF.** Where the menu contradicts itself, use the headline price. Balloon arches are price on application (POA); don't add an arch price.
- **`calculator.html` is private.** It's the owner's price calculator: keep it `noindex`, out of `sitemap.xml`, unlinked from every page and without analytics.

## Working on the site

- Pages: `index.html` (menu, latest setups, reviews, terms), `luxlights.html`, `balloon-arches-glasgow.html` and `privacy.html`.
- Public pages load `/analytics.js` (Cloudflare Web Analytics, plus GA4 only after cookie consent). New public pages also go in `sitemap.xml`.
- Photos go in `images/`, resized to about 1200px wide.
- Test at phone width (390px) as well as desktop.

## Writing

- Follow `~/home-repo/docs/standards.md`: British English, GBP and the Stop Slop rules.
- Friendly and local. Say "Glasgow" where it reads naturally; it helps local search.
