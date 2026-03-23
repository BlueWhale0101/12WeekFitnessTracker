# Hosted iPhone Web App: 12-Week Training & Nutrition Checklist

This folder is ready to deploy as a small hosted web app.

## Files
- `index.html` — the full app
- `manifest.webmanifest` — allows app-like install behavior
- `service-worker.js` — lightweight offline caching
- `icon.svg` — simple app icon
- `README.md` — deployment steps

## Easiest deployment options

### GitHub Pages
1. Create a new GitHub repository.
2. Upload all files from this folder to the root of the repo.
3. In GitHub, go to **Settings > Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/root`.
6. Save. GitHub will publish the site.

### Netlify
1. Create a new site on Netlify.
2. Drag this folder into Netlify Drop, or connect a repo.
3. The site will publish automatically.

### Cloudflare Pages
1. Create a new Pages project.
2. Upload this folder or connect the repo.
3. Build command is not needed.
4. Output directory can stay blank or `/`.

## Use on iPhone
1. Open the live site in Safari.
2. Tap **Share**.
3. Tap **Add to Home Screen**.
4. Turn on **Open as Web App** if prompted.
5. Launch it from your Home Screen.

## Notes
- Checkbox state is saved in local browser storage on that iPhone.
- The app calculates 12 weeks starting from the Monday of the current week when opened.
- Offline support is basic and meant for convenience after the first load.