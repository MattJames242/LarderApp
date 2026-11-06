# Larder Weekly

A weekly meal planner that builds a 7-day menu and an aisle-sorted Lidl shopping list within a budget you set.

It is a Progressive Web App: host this folder on any HTTPS static host (GitHub Pages, Netlify, Cloudflare Pages), open it on your phone and choose **Add to Home Screen**. It then opens full screen with its own icon and works offline.

Files:
- `index.html` – the whole app (no build step)
- `manifest.webmanifest` – name, icon and colours used when installed
- `sw.js` – service worker for offline use
- `icons/` – home-screen icons

Your plan, ticks, prices and avoided foods are stored in the browser on each device.

## Hosting on GitHub Pages

`.github/workflows/pages.yml` publishes the site on every push to `main`. One-time setup: in the repo go to **Settings → Pages → Build and deployment → Source** and choose **GitHub Actions**.
