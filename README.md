# Advanced CrossFit Checklist Web App

This bundle is ready for GitHub Pages, Netlify, or Cloudflare Pages.

## Included
- `index.html` — the full app
- `manifest.webmanifest` — install metadata for Home Screen web app behavior
- `service-worker.js` — basic offline caching
- `icon.svg` — simple app icon
- `README.md` — deployment steps

## Features
- Full 12-week calendar view with Week 1 through Week 12
- Daily Nutrition checkbox
- Daily CrossFit class checkbox
- Weekly workout checklist based on the 12-week training plan
- Weekly weigh-in input
- Weekly notes box
- Local persistence in the browser

## GitHub Pages steps
1. Create a new GitHub repository.
2. Upload all files from this folder to the repo root.
3. In GitHub, open **Settings > Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Pick the `main` branch and the `/root` folder.
6. Save and wait for the published URL.

## Use on iPhone
1. Open the live URL in Safari.
2. Tap **Share**.
3. Tap **Add to Home Screen**.
4. Launch from the Home Screen for an app-like experience.

## Notes
- Progress is saved per browser/device using local storage.
- If you want cloud sync later, this front end can be connected to a lightweight backend.