# Touch DNA Transfer — How Skin-Cell DNA Convicts the Innocent

A single-page educational site about touch (skin-cell) DNA evidence: how DNA
transfers from person to person and object to object, persists for years, and
convicts people who were never there — the documented cases that collapsed,
the current standards movement (NIST IR 8503, SWGDAM, OSAC), and the law
catching up. The lead case study is **Elmo Rivadeneira**, whose full case is
documented on the companion hub, *The Science of Innocence*.

**This is a NEW, separate repository** (sister site to `science-of-innocence`).
It does not modify, replace, or attach to any existing site
(elmorivadeneira.com, the Neocities pages, or the Google Sites hubs). Do **not**
add a CNAME file or a custom domain to this repo.

## Files

- `index.html` — the whole site (one page, no JavaScript of its own)
- `style.css` — the shared dark navy/gold design system (same family as the hub)
- `og-card.jpg` — social share card (1200×630), referenced by og:image
- `sitemap.xml`, `robots.txt` — for Google Search Console
- `404.html` — redirects any missing page back to the home page

## How to publish (GitHub Pages, from the repo root)

1. Create a **new** GitHub repository named `touch-dna-transfer`.
2. Upload all of these files to the repository root (keep the names exactly).
3. In the repo: **Settings → Pages → Build and deployment → Deploy from a
   branch**, choose the `main` branch and `/ (root)`, and save.
4. GitHub publishes it at `https://rivadeneiraelmo.github.io/touch-dna-transfer/`
   — the address already wired into the canonical link, Open Graph tags,
   sitemap, and robots.txt.
5. Enable **Settings → General → Features → Discussions** so the
   "Ask About the Science" board works.
6. In Google Search Console, add the site and submit `sitemap.xml`.

## Suggested repository description

> Touch DNA Transfer — how skin-cell DNA convicts the innocent: secondary DNA
> transfer, innocent transfer, the cases that collapsed, and lead case study
> Elmo Rivadeneira (The Science of Innocence).

## Notes

- Plain HTML/CSS only — no Jekyll, no build step, no external dependencies
  except the embedded YouTube videos.
- Companion hub: https://rivadeneiraelmo.github.io/science-of-innocence/
