# Century Score

Cash aur player scores track karne wali PWA, GitHub Actions se Android APK mein build hoti hai.

## Structure
- `www/` — app files (index.html, manifest, service worker, icons)
- `.github/workflows/build-apk.yml` — APK build workflow
- `capacitor.config.json` — Android wrapper config

## APK kaise milega
1. Repo GitHub par push karein (branch `main`).
2. **Actions** tab → *Build APK* run hone dein (ya "Run workflow" dabayein).
3. Run khulne par neeche **Artifacts → century-score-apk** download karein, zip kholein, `app-debug.apk` phone mein install karein.

## Web (PWA) version
GitHub Pages: Settings → Pages → Deploy from branch → `main` / folder `/www` (ya `/(root)` agar www ko root banayein).
