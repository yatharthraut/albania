# Albania, on the day — field app

Single-file web app for the 25 Sep – 7 Oct 2026 trip. Works offline once opened.

## Put it on GitHub Pages (once, ~5 min)
1. Create a new repo on github.com (public or private), e.g. `albania`.
2. Upload these files to the repo root: `index.html`, `sw.js`, `manifest.json`, `icon-180.png`, `icon-512.png`, `albania.ics`.
3. Repo → Settings → Pages → Source: "Deploy from a branch" → Branch: `main`, folder `/ (root)` → Save.
4. Wait 1–2 min. The app is at `https://<your-username>.github.io/albania/`.

## Install on the phones
- iPhone: open the URL in Safari → Share → Add to Home Screen. Open it once from the icon while online; after that it works with no signal.
- Android: open the URL in Chrome → ⋮ → Add to Home screen (or "Install app").

## Notifications
Open `https://<your-username>.github.io/albania/albania.ics` on each phone and add it to the calendar (iPhone: tap the link → "Add All"; Android: download, then open with Google Calendar). Every stop gets a 30-minute alert, and each day has a wake-up event with the day's summary and bring-list. Times are Europe/Tirane.

## Updating
Replace `index.html` (and `albania.ics` if timings changed) in the repo. Phones pick up the new version the next time they open the app with signal.
