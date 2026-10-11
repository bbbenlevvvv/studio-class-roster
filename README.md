# Studio-Master — interactive class reel
A Hebrew student photo wheel inspired by a vintage stereoscopic viewer reel. Drag the wheel to rotate with momentum and frame snapping. Mouse wheel, arrow keys and previous/next buttons also work. The lower half extends below the viewport.

## Use
Import your private roster JSON using the import button. Names and photos remain in this browser's localStorage; they are not uploaded to a server. Public source contains sample silhouettes only. Export backups regularly; clearing browser storage removes local records. Imports support 1–50 students and JPEG, PNG or WebP data URLs.

## Development
Run `python3 -m http.server 4173` in this folder. Buildless HTML/CSS/JS; no dependencies. Heebo fonts are self-hosted under their included SIL Open Font License.

## Privacy
Never commit private roster files, backups, photos or the original student PDF. The localhost-only private import endpoint is supplied by a separate development server outside this repository. All photos on the public demo are generated SVG silhouettes.
