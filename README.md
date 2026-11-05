# Prompt Workspace Manager — Offline Build

This package contains a self-contained offline build of Prompt Workspace Manager.

## Run

1. Extract the ZIP archive.
2. Open `index.html` in a supported Chromium-based browser (Google Chrome or Microsoft Edge).
3. Select a local workspace folder and start using the application.

The application embeds its CSS and Noto Sans Arabic font files. It does not load Tailwind CSS, fonts, scripts, or other resources from a CDN at runtime, and its core features do not require an internet connection.

The app uses the browser File System Access API. Browser support and local-file permission behavior may vary; Chrome or Edge is recommended.

## Third-party assets

Noto Sans Arabic is embedded in `index.html` and is licensed under the SIL Open Font License 1.1. See `THIRD_PARTY_NOTICES.txt` for the copyright and license text.
