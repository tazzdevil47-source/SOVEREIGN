SOVEREIGN ORIGINAL MINIMAL PATCH

This keeps your original app structure intact.

Changed only:
1. Added PropTypes before Recharts to fix:
   Cannot read properties of undefined (reading 'oneOfType')
   Recharts is not defined

2. Bumped service worker cache from sovereign-v3 to sovereign-v4.

3. Added two Daily Challenge fields:
   - Define the Challenge
   - Challenge Status

4. Added those two fields to the Excel export.

Deploy:
- Upload index.html, sw.js, and manifest.json to your GitHub Pages repo.
- Replace the old files.
- Then clear old browser/PWA cache or uninstall the old PWA first.