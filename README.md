# American Roots website

Program website for American Roots at UCI Teacher Academy.

## Preview

Run `python3 -m http.server 4173 --bind 127.0.0.1` from this directory, then open http://127.0.0.1:4173. No installation or build is needed.

## Files

- `index.html`: page content and navigation
- `styles.css`: responsive layout and brand palette
- `american-roots-logo.png`: supplied American Roots artwork
- `uci-teacher-academy-logo.png`: supplied Teacher Academy artwork

The page uses Cinzel and Open Sans through Google Fonts, with system fallbacks. Original logos retain their colors and proportions.

## Content

Program descriptions, schedules, participation details, team information, and resources still need review. Contact information links to UCI Teacher Academy. Specific requested changes are previewed locally before committing.

## Hosting

Cloudflare setup is deferred. This is a static website with no build step, environment variables, or secrets. Committing files does not deploy a live website.
