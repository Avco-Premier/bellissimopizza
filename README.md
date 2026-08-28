# Bellissimo Pizzeria & Pasta Website

Official website for Bellissimo Pizzeria & Pasta at The Shoppes at East Wind in Wading River, New York.

**Website:** [www.bellissimospizzeria.com](https://www.bellissimospizzeria.com/)

## Pages

- **Homepage** — Bellissimo’s story, food gallery, menu highlights, app downloads, and location preview
- **Menu** — searchable restaurant menu with live ordering data, a saved fallback, and printable PDF
- **Catering** — the complete catering menu, tray pricing, descriptions, search, and printable PDF
- **Visit** — address, hours, contact information, directions, and embedded map

## Local preview

This is a static HTML, CSS, and JavaScript website with no build step.

```bash
python3 -m http.server 8000
```

Then open `http://127.0.0.1:8000/`.

## Project structure

```text
index.html                         Homepage
menu/index.html                    Canonical menu page
catering/index.html                Canonical catering page
visit/index.html                   Canonical visit page
assets/menu-fallback.json          Saved regular-menu fallback
assets/catering-menu-data.js       Catering menu transcribed from Bellissimo’s PDF
menu.pdf                           Printable restaurant menu
catering-menu.pdf                  Printable catering menu
styles.css                         Core responsive design system
enhancements.css / polish.css      Visual enhancements and final layout refinements
script.js / menu-live.js           Shared interactions and menu rendering
robots.txt / sitemap.xml           Search indexing configuration
CNAME                              Production domain configuration
```

The legacy `menu.html` and `catering.html` routes redirect visitors to the canonical page URLs.

## Business information

**Bellissimo Pizzeria & Pasta**<br>
The Shoppes at East Wind<br>
5768 Route 25A, Suite K<br>
Wading River, NY 11792<br>
[(631) 886-1536](tel:+16318861536)
