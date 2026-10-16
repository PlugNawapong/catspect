# CATSPECT

CATch SPECTrum for your solution. Portfolio of a three-person research team building multispectral imaging instruments, bit by bit, out of passion.

The flagship case study is the portable multispectral imaging system for sodium nitrite detection published in *Sensors* (MDPI), DOI: [10.3390/s25237323](https://doi.org/10.3390/s25237323).

## Structure

- `index.html` — the site (single file: HTML, CSS and vanilla JS, no build step)
- `assets/` — web-optimised figures from the paper (`band-r2`, `ndi-map`, …) and instrument photos (`gen2-*`, `gen3-*`) converted from the HEIC originals
- `msi_concept_nitrite_detection.png`, `portable_msi.png` — original full-resolution sources

## Sections

Our story · Projects (01 nitrite imager, 02 20-filter aluminium imager, 03 live plant-health imager) · How we work · What's next · Publication and contact

## Editing

- **Contact email:** set `CONTACT_EMAIL` near the top of the `<script>` block in `index.html`. The email row stays hidden while it is empty.
- **Text and photos:** each project is its own `<section>` (`#p1`, `#p2`, `#p3`) in `index.html`.

## Deploy (GitHub Pages)

Push to a repository, then Settings → Pages → deploy from the `main` branch root. The site will be at `https://<your-username>.github.io/<repo-name>/`.
