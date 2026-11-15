# Cube Solver

Enter the colors of your Rubik's cube and watch the solution as a 3D animation. Works offline after the first load.

## Put it online with GitHub Pages
1. Create a **public** repository on GitHub.
2. Push all files of this folder (`index.html`, `sw.js`, `manifest.webmanifest`, `favicon.svg`, `icons`, `lib`, `.github`) to the `main` branch.
3. Settings -> Pages -> Deploy from a branch -> `main` -> `/ (root)` -> Save.
4. After 1-2 minutes your app is live at `https://YOUR-USERNAME.github.io/REPO-NAME/`

## Install on your phone
Open the link in Chrome -> menu (three dots) -> Install app / Add to Home screen.

## Android APK (automatic)
The workflow in `.github/workflows/build-apk.yml` builds an APK on every push to `main` (or run it by hand from the Actions tab).
When the run is green, open the repository -> **Releases** -> latest release -> download `app-debug.apk` and install it on your phone (allow "Install unknown apps" if asked).

Solver library: cubejs (MIT license), in the `lib/` folder.
