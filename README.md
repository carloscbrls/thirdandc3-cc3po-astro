# Third & C3 — website

Public page for **Third & C3** ("Fantasy football, coached. IDP-first, straight from the film room." — by C3), deployed to **https://thirdandc3.cc3po.com** via Netlify, following the CC3PO one-repo-per-subdomain pattern (`<name>-cc3po-astro` family).

## Layout

- `index.html` — the whole page (self-contained; canonical + OG meta point at thirdandc3.cc3po.com)
- `assets/crest.png` — Third & C3 crest (page hero + OG share image)
- `assets/Oswald.ttf`, `assets/Inter.ttf`, `assets/Yellowtail.ttf` — self-hosted fonts via `@font-face`
- `netlify.toml` — publish root, no build command

## Source of truth

The working copy lives in the Village workspace at `content/cc3po/fantasy-blog/site/` (maintained by Audible, the C3 Sports Desk). League standings on the page carry their verification dates — refresh them from the desk's latest verified scan, never from memory.
