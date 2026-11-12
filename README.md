# American Roots

## WordPress

Paste the contents of `wordpress.html` into a Custom HTML block. Paste `styles.css` into your theme’s Additional CSS area. The #american-roots wrapper scopes the styling to this content. Configure Cinzel and Open Sans through your theme’s font settings; serif and sans-serif fallbacks remain available.

Use a full-width page template if you want the layout to match the standalone preview. WordPress theme styles, content sanitization, and available width still need checking on the actual page.

The supplied revision uses remote image URLs, a Google Drive grant narrative, and a single Teacher Leader application linked to Google Forms. No Teacher Practitioner card is included in that revision.

## Local preview

Run `python3 -m http.server 4173 --bind 127.0.0.1`, then open http://127.0.0.1:4173/. `index.html` provides the standalone preview shell for the same WordPress content. Keep its body content synchronized when changing the WordPress fragment.
