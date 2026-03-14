# ImmoChat Property Listings

This revised package is a root-only static dataset designed for GitHub repository hosting and ZIP downloads.

## What changed

- Replaced `twalk.chat` references with the GitHub repository URL `https://github.com/plill-overlay/immochat`.
- Simplified the dataset to two example listings: `listing-001` and `listing-008`.
- Kept all files in the repository root.
- Added direct image files in root for agent discovery and local ZIP preview.
- Added `ai.json` as an agent-friendly schema hint.

## Discovery flow

1. `index.html`
2. `api.json`
3. `listing-001.html` / `listing-008.html`
4. `listing-001-1.jpg`, `listing-001-2.jpg`, `listing-008-1.jpg`, `listing-008-2.jpg`

## Notes

- The included JPG files are placeholders so the ZIP is complete and image references resolve locally.
- Replace them with real property photos if you have original assets.
