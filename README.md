# Prabhaya website

Static site for the Prabhaya Android app, published via GitHub Pages at
https://madhavramini.github.io/prabhaya/

- `index.html` — landing page (trilingual: EN / తెలుగు / हिन्दी)
- `privacy/index.html` — privacy policy (Play Console URL: https://madhavramini.github.io/prabhaya/privacy/)
- `assets/qr-apk.svg` / `.png` — QR pointing at the stable APK download URL

## APK downloads

APKs are published as GitHub Release assets named exactly `prabhaya.apk`, so the
stable URL always serves the latest release:

https://github.com/madhavramini/prabhaya/releases/latest/download/prabhaya.apk

To publish a new version: create a release with a new tag (e.g. `v0.1.4`) and
attach the APK renamed to `prabhaya.apk`. The QR code and site links keep working.

## Editing

Plain HTML/CSS/JS, no build step. Push to `main` and GitHub Pages republishes.
Language choice persists across pages via the `prabhaya-policy-lang` localStorage key.