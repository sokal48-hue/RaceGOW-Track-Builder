# Changelog

This changelog covers the public RaceGOW Track Designer and the separately developed Flight Path Designer prototype.

## Website / distribution update — permanent app filenames

- Added a GitHub Pages landing page (`index.html`) for launching the tools online.
- Standardized the public application filenames to **`Designer.html`** (Track Designer V71) and **`Route.html`** (Flight Path Designer V28 prototype).
- Updated homepage launch and standalone-download links to those stable filenames; later versions can replace these files without changing homepage URLs.
- This is a **distribution and documentation update**, not a new application version.

## Track Designer V71 — Editor and build-guide improvements

- Focused and zoomed assembly illustrations around the highlighted parts.
- Displayed two build steps side-by-side, flowing downward and onto additional pages.
- Added step-level part names, icons, and quantities.
- Added **Master Reset**, including reset after importing a locked layout.
- Added **Required / Optional** floor-footprint selection for newly added links, including Auto mode, and eligible selected floor links.
- Protected existing required floor-footprint links during bulk floor additions/removals.
- Added right-click context actions for selected links, including endpoints, applicable floor-link classification, and removal.
- Restored complete embedded RaceGOW artwork after a partial-image issue.
- Maintained protected-track edit restrictions.

## Track Designer V70 — Initial public release

- First completed public version of the physical track builder.
- Interactive 6 × 6 × 6 workspace, structure presets, connector and inventory calculations, support planning, JSON import/export and locked layouts, and printable build instructions.

## Flight Path Designer V28 — Prototype progress (not public release)

- Required gate sequences and directional selection before route drawing.
- Repeated gate crossings and sequence-based path colors.
- Freehand mouse drawing with Up/Down elevation changes while the mouse is held.
- Editable checkpoints, turn apexes, and contextual point controls.
- In-workspace tool controls, clean preview mode, and dashed route display.
- Visual cleanup of clustered route points when completing a lap; editing data remains preserved.
- Route coloring, crossing detection, and collision/clearance behavior remain experimental.
