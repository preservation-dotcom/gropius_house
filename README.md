# Gropius House Environmental Atlas Rebuild

This folder contains a rebuilt static homepage for the Gropius House environmental atlas project.

## Included

- `index.html`: new homepage shell and section structure
- `styles.css`: redesigned visual system and responsive layout
- `app.js`: rebuilt interaction layer for the atlas, repairs archive, pest comparison, and image records
- `data.js`: extracted source data used by the new interface
- `assets/`: site plan and linked conservation PDFs used in the new design
- `images/`: recovered original site photos, pest-board photos, and plan images from the shared source package

## Notes

- The first-floor, second-floor, basement, latest-site, and pest-comparison images now point to recovered source files instead of fallback placeholders.
- The 1945 site plan is included in `assets/site-plan-1945.jpg`.
- No archival section/elevation image was present in the recovered source site package, so those blank placeholders were removed from the drawings strip.

## GitHub Upload

Upload these files and folders to the repository root:

- `index.html`
- `styles.css`
- `app.js`
- `data.js`
- `assets/`
- `images/`

Optional to keep:

- `README.md`

If GitHub Pages is already configured for the repo root, the site should publish from `index.html`.
