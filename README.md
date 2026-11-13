# Offline games — GitHub Pages setup (about 3 minutes, all from your phone)

1. Go to github.com, sign in, tap **+ → New repository**. Name it `games`, set it **Public**, create it.
2. Tap **Add file → Upload files**. Upload everything inside this folder (the 8 game .html files, index.html, sw.js, manifest.webmanifest and the icons folder). Commit.
   (On a phone it is easier to unzip first, then upload; folders may need the desktop site.)
3. **Settings → Pages**: Source = *Deploy from a branch*, Branch = `main`, folder `/ (root)`. Save.
4. After ~1 minute your site is live at  https://YOUR-USERNAME.github.io/games/
5. Open that link in **Safari** while online. Wait until it says "✓ Saved for offline play".
6. Tap **Share → Add to Home Screen**.
7. Test: turn on airplane mode and open the Home Screen icon. Everything works offline.

Notes
- Open the app once online after any update so it refreshes its saved copy (bump `V` in sw.js to force it).
- If you clear Safari website data, the offline copy is deleted; just open the link online again.
