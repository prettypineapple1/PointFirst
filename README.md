# Point First

Daily practice for clear speaking and writing. A static web app: no build step, no server, no accounts.

Files: `index.html` (the whole app), `manifest.webmanifest` + `sw.js` + the four `icon-*.png` / `apple-touch-icon.png` files (make it installable and work offline).

## Publish for free
- **Netlify Drop:** go to app.netlify.com/drop on a computer and drag this whole folder onto the page. You get a link right away.
- **Cloudflare Pages:** Workers & Pages > Create > Pages > Upload assets, then upload this folder.
- **GitHub Pages:** put these files in a repo, then Settings > Pages > deploy from the main branch.

## Install on a phone
- **iPhone (Safari):** open the link, tap Share, then Add to Home Screen.
- **Android (Chrome):** open the link, tap the menu, then Install app.

## Updating later
Change `index.html`, then bump `CACHE` in `sw.js` (for example `point-first-v2`) so installed copies pick up the new version.
Progress (XP, streak, unlocked lessons) is stored in the browser on each device and does not sync between devices.
