# Shas Page Layout HTML

Public static HTML export of ready page-layout pages.

## Structure

- `index.html` - top-level tractate index.
- `tractate/<tractate>/index.html` - index for one tractate.
- `tractate/<tractate>/<page>.html` - rendered page-layout page.
- `assets/fonts/frank-ruhl-libre/` - Frank Ruhl Libre (gemara body / page header).
- `assets/fonts/mekorot/` - Mekorot Rashi (rashi and tosafot streams).
- `manifest.json` - machine-readable list of included pages.

## Current Contents

- Berakhot: `2a` through `64a`, 125 pages.

The repository is intended to grow to all Shas while keeping the same folder
layout. Bundled fonts must be open-license fonts only. Bundled open fonts
currently include Frank Ruhl Libre and Mekorot, both under SIL OFL 1.1.
