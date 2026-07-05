# Trailhead — Fitness Log

A simple installable web app (PWA) for tracking weight, walks (with live GPS distance + photos), calories, and steps. No login, no backend — all data is saved privately in the browser it's used on.

## Files
- `index.html` — the whole app
- `manifest.json` — makes it installable as an app
- `sw.js` — lets it work offline once loaded
- `icon-192.png`, `icon-512.png` — app icons

## Deploy with GitHub Pages (free)

1. Go to your GitHub account and click **New** to create a repository (e.g. `dad-fitness-tracker`). Keep it **Public**.
2. On the new repo page, click **uploading an existing file** and drag in all 5 files above.
3. Commit the files (green "Commit changes" button).
4. Go to the repo's **Settings** tab → **Pages** (left sidebar).
5. Under "Build and deployment", set **Source** to **Deploy from a branch**, branch **main**, folder **/ (root)**. Click **Save**.
6. Wait about a minute, then refresh — GitHub will show your live link, something like:
   `https://yourusername.github.io/dad-fitness-tracker/`

Send that link to your dad. He doesn't need a GitHub account or any login — he just opens it.

## Installing as an app (optional, for your dad)
- **iPhone:** open the link in Safari → tap the Share icon → **Add to Home Screen**.
- **Android:** open the link in Chrome → tap the ⋮ menu → **Add to Home screen** (or **Install app**).

## Making future edits
Come back to this chat, describe the change you want, and I'll update the code. Then just re-upload the changed file(s) to the same GitHub repo (drag-and-drop over the old ones — GitHub will ask to confirm the update) and the live site updates automatically within a minute.

## Notes on this first version ("the bones")
- **Weight:** manual entry + trend chart.
- **Walks:** tap Start to track live via GPS (time, distance, pace, path sketch); temperature is entered manually after stopping (no weather API hooked up yet); photos can be attached after saving. Manual entry is also available for walks you forgot to track live.
- **Calories:** save reusable meal presets (tap to log instantly) or add one-off custom items; shows today's total and past days.
- **Steps:** manual daily entry with a 14-day bar chart (most phones don't expose step data to a plain website, so this is manual for now — we can revisit if he uses a phone/watch with an API we can connect).
