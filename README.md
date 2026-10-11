# Studio — interactive class roster
A Hebrew, right-to-left class roster. Buildless HTML, CSS and JavaScript.

## Use
Open the site and import your private roster JSON. Data stays in localStorage in that browser and origin; it is not synced between devices or transmitted to a backend. Export backups regularly. Clearing browser storage removes local records. Use attendance by date, edit students and notes, randomly pick students without repeating within a round, and create balanced groups.

## Development
Run `python3 -m http.server 4173` in this directory. No dependencies or build step.

## Private data
Source contains demo students only. Never commit roster imports, backups, photos or the original PDF. The localhost-only import endpoint is supplied by a separate development server outside this repository. Review names and contact fields after importing.
