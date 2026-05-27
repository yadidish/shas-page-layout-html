# Shas Tzurat HaDaf HTML

Public static HTML export of ready Tzurat HaDaf pages.

## Structure

- `index.html` - top-level masechet index.
- `masechtot/<masechet>/index.html` - index for one masechet.
- `masechtot/<masechet>/<amud>.html` - rendered daf/amud page.
- `assets/fonts/noto/` - open fonts required by the HTML pages.
- `manifest.json` - machine-readable list of included pages.

## Current Contents

- Berakhot: `2a` through `64a`, 125 amudim.

The repository is intended to grow to all Shas while keeping the same folder
layout. Bundled fonts must be open-license fonts only.
