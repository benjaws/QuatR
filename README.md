# QuatR

**A simplified Gantt roadmap for planning animal experimentation projects around the 3Rs: Replace, Reduce, Refine.**

A single HTML file: no install, no server, no account. Open it in a browser and build your roadmap by drag and drop.

**[Try it online](https://benjaws.github.io/quatr/)**

![QuatR preview](docs/screenshot.png)

## Features

- **Drag-and-drop blocks**: create a block, then drop it into the section and year you want.
- **Backlog**: blocks not yet scheduled wait under the creation bar. Drag them onto the Gantt, or send them back to the backlog.
- **Side-by-side blocks**: several blocks can share the same row within a year.
- **1 to 3 years long**: stretch a block with its right-hand handle. It snaps to 1, 2 or 3 years.
- **Dependency arrows**: drag from a block's purple dot to another block. Click an arrow to delete it.
- **Editable sections and years**: rename sections, add or remove sections and years.
- **PDF export / print**: landscape layout ready to print. In an embedded preview, a printable page opens in a new tab.

## Usage

1. Open `index.html` in your browser (Chrome, Edge, Firefox, Safari).
2. Type a name, pick a color, click **Add block**.
3. Drag the block onto the Gantt.
4. Stretch it, link it to other blocks, then click **Export PDF / Print**.

An internet connection is required on load: Tailwind CSS, Font Awesome and the Inter font are loaded from CDNs.

## Current limitations

- Data is not saved: reload the page and the roadmap goes back to the starting example.
- No data export (JSON) yet.

## License

[MIT](LICENSE)
