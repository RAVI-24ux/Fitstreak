# FitStreak — Android-friendly workout tracker

## Quick start
Open `index.html` to preview the tracker. For installability and offline support, host the folder on an HTTPS static host.

## Deploy free with GitHub Pages
1. Create a new GitHub repository (for example `fitstreak`).
2. Upload all files and the `icons` folder from this package.
3. In the repository, open **Settings → Pages**.
4. Choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
5. Wait for the published HTTPS URL shown in Pages.

## Install on Android
1. Open the published HTTPS URL in Chrome.
2. Tap **⋮ → Install app** or **Add to Home screen**.
3. Confirm. FitStreak will appear in your app drawer/home screen.
4. Open it once online so its files are cached; it can then load offline.

## Notes
- PWA installation requires a secure HTTPS origin (or localhost for development); opening the HTML file directly does not install it as an app.
- Workout data is saved in local browser storage on that device. Use **Export backup** periodically. Clearing Chrome/site data can erase local progress.
- This is a PWA, not an Android APK or a live-updating home-screen widget.
