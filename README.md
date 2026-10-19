# ONE DAY — Version 0.1

A no-cost, static, installable web app prototype for daily recovery check-ins and self-paced craving support.

## Features
- Daily mood check-ins and optional private notes
- Encouragement messages and milestone badges
- Five-step guided craving support (self-paced; **not a timed service**)
- Trusted contact phone link
- Export and erase locally stored data
- Installable PWA and basic offline support after first visit

## Important limitations
- **There is no AI chat in this version.** A safely deployed AI companion requires an appropriately secured backend, safety design, privacy disclosures, testing, and likely usage costs. Never put API keys inside browser JavaScript.
- There is no login, cross-device sync, real crisis monitoring, automated contact, or medical advice.
- Data is saved only in the user's browser (`localStorage`). It is **not encrypted**; clearing browser storage or changing devices can erase it. This version is a prototype, not a production-ready system for sensitive health information.
- The five support steps represent a suggested 10-minute pause; users advance manually, without an actual countdown.
- Emergency details include Ireland's numbers 112 and 999 as examples. Localize resource links and thoroughly review safety language before launch.
- The SVG icon works on many devices, but for full iOS/Android install-icon coverage, add PNG icons later.

## Run locally
Open `index.html` in a browser for a quick preview. For PWA/offline testing serve the folder on localhost, e.g. `python3 -m http.server 8080`, then browse `http://localhost:8080`.

## Publish for free using GitHub Pages
1. Register for a free account at github.com.
2. Create a **public** repository called `one-day-app` (or your choice).
3. Upload **the files INSIDE this folder** to the repository root (not the ZIP and not the enclosing folder). Include `.nojekyll` if possible.
4. Go to repository **Settings > Pages** and set **Source: Deploy from a branch**, **Branch: main**, folder **/(root)**; then **Save**.
5. GitHub publishes at `https://YOUR-USERNAME.github.io/one-day-app/` (replace YOUR-USERNAME and repository name).
6. On Android: open it in Chrome and look for **Install app** / **Add to Home screen**. On iPhone: open in Safari, tap Share, then **Add to Home Screen**. Availability varies by device/browser.

GitHub Pages requires a public repository on the GitHub Free plan. Never upload personal check-in data or API secrets to the repository. Your published site and its source files will be public.

## Privacy & safety before real launch
Get clinical/safeguarding review, appropriate legal/privacy review, clear age policy and consent, accessibility testing, device/browser testing, and accurate localized crisis resources. This should not be marketed as clinical treatment or an emergency responder.
