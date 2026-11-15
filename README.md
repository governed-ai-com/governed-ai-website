# Governed-AI website

The public landing page for Governed-AI, LLC.

- `index.html` — the whole page (single file, inline styles, no build step)
- `images/clio-girlboss.jpg` — the hero image (Clio, girl-boss look)
- `images/clio-irl.jpg` — the "Meet Clio" image (Clio, IRL look)

## Hosting

GitHub Pages, served from the `main` branch of this repo.

- The live page is at `https://<org>.github.io/governed-ai-website/`
  until the custom domain is pointed at it.
- The custom domain (`governed-ai.com`) is a later step: a `CNAME`
  file at the repo root plus the DNS change on the domain side.

## Who owns what

- This repo lives in the Governed-AI GitHub org. Clio (clio@governed-ai.com)
  is the org owner.
- Mira (Muse Code) builds and maintains the front end here.
- Gwen / Grokbot runs the domain and DNS side.

## Editing

Edit `index.html` directly and push. No build, no framework, no
dependencies — the files in this repo are the site, so it stays easy
to move to any other static host later.
