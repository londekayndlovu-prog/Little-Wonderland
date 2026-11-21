# Little Wonderland

Toddler-friendly puzzle games (ages 2-6) with endless procedurally generated puzzles:
Magic Blocks, Rainbow Liquids, Magic Numbers, Mahjong Adventure and Bus Jam.
No ads, no in-app purchases, no timers, no lives. Progress saves in the browser and the game works offline after the first visit.

## Publish on GitHub Pages
1. Create a new repository on GitHub (for example `little-wonderland`).
2. Upload everything in this folder to the repository root (drag and drop into the web page, or use git).
3. Go to **Settings > Pages**. Under **Build and deployment**, choose **Deploy from a branch**, pick `main` and `/ (root)`, then Save.
4. After a minute the game is live at `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

On a phone, open that link and use **Add to Home Screen** to install it like an app.

## Files
- `index.html` - the whole game (single file)
- `manifest.webmanifest`, `sw.js` - installable and offline support
- `icon.svg`, `icon-*.png` - app icons
- `.nojekyll` - tells GitHub Pages to serve the files as they are

Note: fonts load from Google Fonts when online; the game falls back to a system font offline.
