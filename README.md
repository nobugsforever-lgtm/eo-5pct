# EO Forum 5% Reflection Companion

Bilingual (Chinese + English) monthly reflection prep tool for EO Forum members.

**Live demo:** _set this to your GitHub Pages URL after deploying_

## What it is

A self-contained web tool that walks Forum members through their monthly 5% prep — Life Quality Dashboard, weather report, four reflection areas, parking lot. Includes the NVC feelings inventory, 10/10/80 ratio enforcement, and "dig deeper" iceberg prompts.

All data stays in the user's browser via `localStorage`. No accounts, no servers, no analytics. Nothing leaves the device.

## How to deploy on GitHub Pages

1. Create a new GitHub repository (e.g., `eo-5pct`)
2. Upload all files in this folder (`index.html`, `manifest.json`, `README.md`) to the repo's main branch
3. In repo Settings → Pages → set Source to `Deploy from a branch`, branch `main`, folder `/ (root)`
4. Save. After ~1 minute, your site will be live at `https://<your-username>.github.io/eo-5pct/`

## How to install on iPhone

1. Open the GitHub Pages URL in Safari
2. Tap the Share button (square with arrow)
3. Scroll down → tap "Add to Home Screen"
4. Tap "Add"
5. The icon appears on your home screen and opens full-screen, no Safari chrome

## Privacy

The tool is just a form. Members' reflections live only in their own browser's `localStorage`. The tool can be public; the data is not.

## Files

| File | Purpose |
|---|---|
| `index.html` | The complete tool — single self-contained file |
| `manifest.json` | PWA manifest for "Add to Home Screen" on iOS/Android |
| `README.md` | This file |

## License

Private use within EO Forum context. Not affiliated with EO global.
