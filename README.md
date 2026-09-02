# Laser Level Dirtworks — Google Ads landing pages

Pages: `/` (Demolition), `/excavation`, `/dirt-work`, `/land-clearing` — deployed from this repo root to laserleveldirtworks.vercel.app (customleadz-sites/laserleveldirtworks).

- **Ad ↔ page alignment:** aligned 2026-09-02 to the live ads in campaign `NEW | Leads | search`. Map + history: `google-ads/campaigns/ad-page-alignment.md`. If the ads change, re-run the alignment pass (text only).
- **Forms:** Web3Forms (key in each page's hidden input; leads → Laserleveldirtworks@gmail.com), fires Google Ads conversion `Quote Form Submit`. Free plan = browser-only; curl tests always fail — test in a browser.
- **Tracking:** gtag AW-11509853415 + website-call phone snippet on every page.
- **Images/video:** serve the `.webp` files; originals (`.png/.jpg/.mov`) stay in `assets/` — never delete renamed assets. Hero video = `assets/hero-demolition.mp4` (+ poster). `vercel.json` sets immutable caching on assets.
- **Open items:** hours line (page says Mon–Fri 8–5; ads run Mon–Sat 7–7), FAQ block, stock-photo swap on the demolition page — see the alignment file.
- Changes log for the ad account: `google-ads/reports/2026-09-02-changes.md`.
