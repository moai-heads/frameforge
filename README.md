# FrameForge

A lightweight, browser-based vector drawing and frame animation studio. No build step or dependencies—GitHub Pages serves the app directly from `index.html`.

## Use it

Open the [FrameForge app](https://moai-heads.github.io/frameforge/) in a modern browser. Draw with the toolbar, edit selected objects in Properties, and use the timeline to add keyframes. **Save project** downloads a `.ffx.json` project; **Open** loads one. Export artwork as SVG or PNG.

## Run locally

Open `index.html` directly in a browser, or run a static web server in this folder, e.g. `python -m http.server 8000`.

## Keyboard shortcuts

- `V` select · `P` freehand · `R` rectangle · `O` ellipse · `L` line · `T` text
- `Delete` remove selection · `Ctrl/Cmd+Z` undo · `Ctrl/Cmd+Shift+Z` redo
- `F6` insert keyframe · `Space` temporarily pan

## License

MIT
