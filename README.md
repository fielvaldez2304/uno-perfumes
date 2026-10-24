# UNO PERFUMES — Scent Archive (Test 03)

Test 03 is built from Test 02 with the two requested refinements:
- Removed the small vertical side label beside the hero artwork.
- Replaced the old logo with the user's newer background-transparent white UNO monogram, cropped to remove excess transparent padding and displayed with `contain` so it is not cropped.

The existing collection, replacement bottle images, illustrated top/heart/middle/base note charts, accord bars, search, and navigation remain in place.

## Preview locally
Open `index.html` in a browser. For consistent local behavior, run a small server from this folder:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish with GitHub Pages
1. Create a new GitHub repository.
2. Upload `index.html` and the complete `assets` folder, preserving the folder structure.
3. Open repository **Settings → Pages** and select deployment from the `main` branch and `/ (root)`.
4. Save and open the published Pages URL after deployment completes.

## Notes
- The corrected fragrance name is **Anomaly**, not “Our Anomaly.”
- All bottle images preserve their aspect ratios; they are contained in consistent image stages rather than stretched.
- Note-board images are from the user's supplied charts. Text note lists remain available for accessibility and quick reading.
- Accord bar lengths are illustrative relative rankings, not measured percentages.
