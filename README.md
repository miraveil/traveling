# Wander Journal

An English travel publication with five responsive pages, built with HTML, CSS and JavaScript. No installation or build step is required.

## Pages
- `index.html` — Home
- `explore.html` — Explore category with filters and sorting
- `hot.html` — Hot seasonal stories with filters and sorting
- `winter-destinations.html` — Five places to visit in winter
- `vietnam-december.html` — Vietnam in December

## Preview
Run `python3 -m http.server 8080` from this directory and open http://localhost:8080.

## Features
Responsive layouts, keyboard-accessible navigation, search, category filters, sorting, article table of contents, reading progress, browser-local bookmarks, and copy-link sharing. There is no backend or account system. Bookmarks stay in the current browser.

## Palette
Amaranth `#933B5B`, Thulian Pink `#B5728A`, Brook Green `#AABAAE`, Chalk `#E3D6BF`, Pomelo Olive `#9F9679`.

## Hosting
The included workflow deploys the site after pushes to `main` once **Settings → Pages → Source → GitHub Actions** is enabled in the repository. The expected URL is https://miraveil.github.io/traveling/ after a successful deployment. It is not a deployment confirmation.

## Assets and content
Photos are downloaded from Unsplash and stored in `assets/` so they work without a third-party image host. Fonts are Playfair Display and DM Sans from Google Fonts, with local serif/sans-serif fallbacks. The English copy is original demonstration editorial content; seasonal conditions should be verified before real travel.

Photo sources:
- Coast: https://unsplash.com/photos/1516483638261-f4dbaf036963 (image ID; original CDN: https://images.unsplash.com/photo-1516483638261-f4dbaf036963)
- Vietnam: https://images.unsplash.com/photo-1528127269322-539801943592
- Winter: https://images.unsplash.com/photo-1483664852095-d6cc6870702d
- Alps: https://images.unsplash.com/photo-1476514525535-07fb3b4ae5f1
