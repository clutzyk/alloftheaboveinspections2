# All of the Above Inspections — Quick Site Fix

This bundle updates:
- Email address everywhere to **christopher@alloftheaboveinspections.com**
- Attic Insulation image block to a clean, responsive picture (placeholder provided)

## Deploy steps
1) Upload/replace files in your repo:
   - Put `index.html` at your site root.
   - Put `assets/images/attic-insulation.svg` in the same path structure.
2) Commit & push, let Netlify build.
3) In Netlify → Site settings → Forms → Notifications, set the **contact** form to send to **christopher@alloftheaboveinspections.com**.
4) Optional: Replace the placeholder SVG with a real photo:
   - Save your photo as `/assets/images/attic-insulation.jpg` (and optionally `.webp`)
   - Update the `<picture>` sources in `index.html` if desired.

Need help placing these into your framework (React/Next/Vite/Jekyll/etc.)? Tell me your stack and file paths.