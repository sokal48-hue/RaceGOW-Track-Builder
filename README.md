# 🏁 RaceGOW Design Tools

**Build it. Share it. Race it.**

Free, browser-based tools for designing RaceGOW FPV racing structures and planning flight routes. The public **Track Designer is V71**; the separate **Flight Path Designer is V28 (prototype)**.

## Launch or download

| Tool | Open in browser | Download standalone HTML | Status |
| --- | --- | --- | --- |
| Track Designer V71 | [Launch Track Designer](Designer.html) | [Download `Designer.html`](Designer.html) | Public release |
| Flight Path Designer V28 | [Open Flight Path Designer](Route.html) | [Download `Route.html`](Route.html) | Prototype — testing |

**[Open the RaceGOW website](https://sokal48-hue.github.io/RaceGOW-Track-Builder/)** to choose a tool. To use a tool offline, download its HTML file and open it in a modern browser; the apps are standalone.

**Permanent filenames:** `Designer.html` and `Route.html` are the public app filenames. When new builds are ready, replace these files in the repository while leaving homepage links unchanged. The version numbers remain visible inside the apps. Archived/version-numbered releases can be kept separately.

## Track Designer — V71

Design the physical course in an interactive **6 × 6 × 6** workspace.

- Rotate and zoom the track; add, move, replace, and remove links.
- Create vertical/horizontal gates, cubes, and START/FINISH structures with presets.
- Calculate elbows, Tees, 3-way, 4-way, and 5-way connectors and compare requirements with the standard kit.
- Add half-grid supports and Required or Optional floor-footprint links; bulk removal protects required floor links.
- Right-click links for contextual editing, where permitted.
- Import/export JSON track layouts; share locked layouts that protect the main structure while allowing eligible floor/support edits.
- Use **Master Reset** to clear a design, including an imported locked design.
- Print multi-angle build views and **two assembly steps per row** with automatically focused highlighted parts, part icons, names, and quantities.

## Flight Path Designer — V28 prototype

Plan a route over an imported track, including required gate selection and direction, repeated passages, mouse-drawn paths, elevation changes while drawing (↑/↓), editable checkpoints and turn apexes, and a simplified, color-coded dashed lap preview. Each required gate in the sequence can have its own route color. **This tool is a prototype:** gate-crossing validation, collision clearances, and full browser testing are not complete.

## Sample tracks

- 🔓 [Track 2 — Editable](RaceGOW_Track_2_unlocked_EDITABLE.json): explore and modify a sample track.
- 🔒 [Track 3 — Locked](RaceGOW6_Track__3_LOCKED.json): functional test course with protected main structure and eligible floor/support adjustments.

Download a sample JSON file and open it with the Track Designer's **Import** control.

## Hosting and updating

This repository is designed for **GitHub Pages**, with `index.html` as its homepage. Keep `index.html`, `Designer.html`, and `Route.html` in the published repository folder. The homepage links directly to the stable filenames, including the standalone download controls.

For future public updates, replace the corresponding fixed-name HTML file, update `README.md` and `CHANGELOG.md`, and add version-specific release notes. Prototype Flight Path Designer updates may be shared as single HTML files until a full public release.

## Feedback and contact

The RaceGOW team and community are welcome to try the tools and provide feedback. Use [GitHub Issues](https://github.com/sokal48-hue/RaceGOW-Track-Builder/issues) or contact **RaceGOW registration #569** through Discord.

## License and safety

See [`LICENSE`](LICENSE) for the applicable licensing terms. The Track Designer is a planning aid, not a structural certification; verify physical clearances, connections, stability, and component availability before building or racing. Flight path previews do not guarantee safe or physically flyable routes.
