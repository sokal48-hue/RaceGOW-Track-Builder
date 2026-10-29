# 🏁 RaceGOW Track Designer V71

**Build it. Share it. Race it.**

A standalone, browser-based 3D track design and construction planning tool for the RaceGOW FPV racing community. Design custom racing structures in a **6 × 6 × 6 grid**, plan the parts required, and share printable build instructions.

## Quick start

1. Download [`RaceGOW_Track_Designer_v71.html`](RaceGOW_Track_Designer_v71.html) (or use the [Releases](../../releases) page).
2. Open the HTML file in a modern desktop browser such as Chrome, Firefox, Edge, or Safari.
3. Create a track in the interactive 3D workspace, using presets or individual links.
4. Export your design as JSON to save or share it with another racer.
5. Use the built-in print feature to prepare assembly views and a component summary.

**No installation, account, server, or internet connection is required after download.** The HTML application contains its own styling, scripts, and visual assets.

## Capabilities

- **Interactive 3D course layout:** rotate and zoom the 6 × 6 × 6 track building space; add, select, move, replace, and remove links.
- **Gate and structure presets:** build square gates, cubes, vertical and horizontal START/FINISH structures, and customized connected layouts.
- **Automatic connector planning:** identifies elbows, Tees, 3-way, 4-way, and 5-way joints required by a design.
- **Live inventory comparison:** tracks structural links and connectors against the standard kit and highlights additional parts needed.
- **Floor and support options:** add Required or Optional footprint links and half-grid supports; bulk floor-link changes preserve existing required floor links.
- **Link editing:** right-click links for contextual actions such as selecting endpoints, changing eligible floor-link status, and removing links.
- **Master Reset:** clear the current design and start over, including after importing a locked layout, without refreshing the page.
- **Track sharing:** export/import JSON; export a protected layout in which the main structure is locked while optional floor/support adjustments remain possible in the app.
- **Printable build documentation:** multi-angle track views; two assembly steps per row with centered, zoomed illustrations of highlighted parts; and step-specific component names, icons, and quantities.

## Saving and sharing tracks

The **HTML file is the application**; a **JSON export is a saved track design**. Share the HTML with anyone who needs the builder and a JSON export with anyone who needs to load a specific layout. Use the application's Import control to open a JSON track design.

> **Protected layouts:** The locked export option limits editing through the application's interface. It is a convenience feature for standardized race layouts, **not cryptographic security or tamper protection**.

## Example track files

- 🔓 **[Track 2 — Editable](RaceGOW_Track_2_unlocked_EDITABLE.json):** An unrestricted example to explore editing and construction features.
- 🔒 **[Track 3 — Locked](RaceGOW6_Track__3_LOCKED.json):** A functional test layout with its main structure protected and eligible floor/support adjustments available.

Download the JSON file and open it using the app's **Import** control.

## Project status

- **V71 (current):** Updated assembly-step layouts and component labels, improved floor-footprint Required/Optional controls, contextual link actions, Master Reset, and corrected embedded artwork.
- **V70:** First completed public release of the physical track builder.
- **RaceGOW Flight Route Designer:** Separate companion application in development for gate sequences, crossing directions, adjustable racing lines, and animated lap previews. **Not included** in this release.

## Feedback and contact

The RaceGOW race team and community are welcome to try and share the application. For corrections, requests, or suggestions, open a GitHub Issue (if enabled) or contact **RaceGOW registration #569** through the RaceGOW Discord community.

## Permissions and license

Refer to the repository’s [`LICENSE`](LICENSE) file for the applicable permissions and conditions. 

## Disclaimer

This is a planning tool. Before using any design, verify physical clearances, connection fit, material availability, stability, and assembly safety. A track diagram is not a structural certification.
