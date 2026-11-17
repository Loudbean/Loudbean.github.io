# loudbean.github.io

Static site served by GitHub Pages.

- `/` (`index.html`, `assets/css/home.css`, `assets/images/`) the Loudbean home page: an intro, a card per app and a "Recently" list. It's plain HTML with no Jekyll layout, so edit it directly. To add an app, copy a `.card` block and set its `--tint` colour and icon.

- `/bubby/` support, privacy and terms pages for the Bubby app. Fill in the `[BRACKETED]` items.
- `/.well-known/apple-app-site-association` lets iOS open the Bubby app from `https://loudbean.github.io/bubby/epic-callback`. Replace `LS4AX9P2FU` with the Apple Developer Team ID, and keep the bundle identifier in step with the app.
