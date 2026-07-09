# Portal / App Decoupling — Click-through Prototype

Rough, static HTML/CSS prototype for the Portal/App Decoupling discussion with Gramoz and Vincenz. No build step — open any `.html` file directly in a browser, or view the [live version](../../).

## Files

- `builder.html` — current Studio Builder experience (L0 sidebar, spaces table, packages table). Start here.
- `ide.html` — the builder/analyst IDE (asset editor) opened from a package.
- `apps.html` — the proposed new Apps landing page for Business Users: search-first, Favorites/Recently Opened filters, asset table.
- `asset-view.html` — the proposed asset consumption view opened from Apps.
- `styles.css` — shared design tokens (colors, spacing) and styles for all screens.

## Flow to click through

1. Open `builder.html` — this is today's Studio experience.
2. Click "Open Apps" in the header (or a package's Share → "Open in Apps") to jump to the new Apps experience.
3. From `apps.html`, click any asset row to land on `asset-view.html`.

See `ideations/portal-app-decoupling` and `artifacts/prep-portal-app-decoupling-gramoz-vincenz-2026-07-08` in the wiki for the underlying rationale (not included in this published prototype).
