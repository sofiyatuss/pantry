# Pantry House V1

A free, illustrated, mobile-friendly household pantry and grocery list web app. No account, build step, backend, or dependencies.

## Run locally
Open `index.html` in a modern browser. For a local server, run `python3 -m http.server 8000` in this folder and visit `http://localhost:8000`.

## Publish on GitHub Pages
1. Create a new public GitHub repository (for example `pantry-house`).
2. Upload `index.html`, `style.css`, and `app.js` to the repository root.
3. Open **Settings → Pages** and set **Deploy from a branch**, branch **main**, folder **/(root)**. Save.
4. Open the Pages URL shown by GitHub once deployment completes. On iPhone or iPad, use Safari → Share → Add to Home Screen.

## Features
- Illustrated, tappable kitchen with pantry, fridge, and freezer
- Inventory search, quantity adjustment, editing and deletion
- Automatic shopping list based on minimum desired stock
- Manual family shopping requests
- Shopping checkboxes and one-tap transfer of purchased groceries into inventory
- Expiration watch and due-soon summaries
- Local persistence using browser localStorage
- JSON backup export and import

## Important limitations
- V1 stores data **on each browser/device separately**. It does **not** sync across family members. Shared real-time family syncing requires a backend and authentication in a later release.
- Dates are user-entered. The app cannot detect when groceries are physically consumed or expired.
- Imported backups replace current data after confirmation.
- The sample pantry is only a demonstration; edit or delete the sample items to reflect your home.
- Use Export regularly. Browser storage can be cleared or lost, especially in private browsing.
- “Best before” and “use by” have different food-safety meanings; this app does not determine whether food is safe to eat.
