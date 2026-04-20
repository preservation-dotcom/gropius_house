# Gropius House Environmental Atlas Rebuild

This folder contains a rebuilt static homepage for the Gropius House environmental atlas project.

## Included

- `index.html`: new homepage shell and section structure
- `styles.css`: redesigned visual system and responsive layout
- `app.js`: rebuilt interaction layer for the atlas, repairs archive, pest comparison, and image records
- `data.js`: extracted source data used by the new interface
- `assets/`: site plan and graph images used in the new design
- `current-site.html`: preserved source snapshot used to extract the original dataset

## Notes

- The floor plan images used in the atlas are preserved from the original source and embedded through `data.js`.
- The `Latest Site Images` and `Pest Comparison` sections preserve the original image slots and labels.
- If you later recover the old `images/` folder, place it next to `index.html` and those cards will automatically render the original visuals again.

## GitHub Upload

Upload these files and folders to the repository root:

- `index.html`
- `styles.css`
- `app.js`
- `data.js`
- `assets/`

Optional to keep:

- `README.md`
- `current-site.html`

If GitHub Pages is already configured for the repo root, the site should publish from `index.html`.
