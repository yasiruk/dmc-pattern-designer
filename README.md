# DMC Pattern Designer

A single-file, no-dependency web app for designing counted cross-stitch charts with real DMC floss colours and printing them to A4.

**Live app:** https://yasiruk.github.io/dmc-pattern-designer/

## Features

- **Grid canvas** up to 120 × 120 stitches with configurable cell size.
- **~450 DMC floss colours** with code + name, searchable by number or name.
- **Paint / erase / flood-fill** tools (click or drag).
- **Symbols mode** — overlay a unique symbol per colour so charts stay usable in black & white.
- **Fabric count** (11/14/16/18 ct Aida, evenweave, linen …) with a live finished-size readout in inches and cm, including "stitch over 2" for linen/evenweave.
- **Print to A4** — hides the UI and prints just the chart (with major gridlines every 10 stitches) plus an auto-generated colour key.
- **Save / Load** patterns as JSON.

## Usage

Just open `index.html` in any browser, or visit the live app. Everything runs client-side — no account, no server, no tracking.

When printing, enable **"Background graphics"** in the browser's print dialog so the cell colours render.

## Notes

- On-screen colours are approximations. Screens aren't colour-managed and dye lots vary, so treat the **DMC number** as the source of truth when buying thread.
- Fabric count sets the *finished stitched size*, not the printed chart size — cross-stitch charts are printed at a readable size and counted onto the cloth.
