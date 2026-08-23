# ORBIT V11

ORBIT V11 fixes the live-feed and category-routing failures from V10.

- Uses GDELT directly through JSONP, avoiding the public RSS proxy that could fail in the browser.
- Keeps each category's cache separate so a failed category never jumps back to For You.
- Refreshes the selected category only and sorts newest first.
- Uses publisher-provided images when available and never generates news images.
- Enriches the first stories with GDELT Context snippets after the first paint when available.
- Supports dark/light mode and the existing language/country preferences.

Deploy `index.html`, `manifest.json`, and `sw.js` to the GitHub Pages branch. `README.md` is documentation only.

Test with `?v=11` after deployment to bypass an old browser URL/cache.
