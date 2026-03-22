# Git DAG Visualizer

Paste your `git log --oneline --graph --all --decorate` output and get a beautiful, interactive branch graph visualization.

![FunForrest palette](https://img.shields.io/badge/palette-FunForrest-E5591C)

## Features

- **Paste & visualize** — paste git log output, get an animated DAG instantly
- **Interactive** — zoom, pan, hover for commit details, click to select
- **Two layouts** — top-down tree or left-to-right horizontal
- **Branch filtering** — toggle branch visibility
- **Merge detection** — diamond nodes for merge commits, dashed lines for merge edges
- **Export SVG** — download your graph as a vector image
- **Touch support** — pinch to zoom, drag to pan on mobile
- **FunForrest palette** — dark background, gold nodes, orange accents, subtle glow effects

## Usage

1. Open `index.html` in any browser
2. Paste the output of:
   ```bash
   git log --oneline --graph --all --decorate
   ```
3. Click **Visualize** (or it auto-parses on paste)
4. Zoom with scroll wheel, drag to pan, hover nodes for details

## Quick Start

```bash
# Generate and copy your git log
git log --oneline --graph --all --decorate | pbcopy

# Open the visualizer
open index.html
# Paste and visualize!
```

## Zero Dependencies

Single HTML file. No build tools, no frameworks, no npm install. Just open and use.

## License

MIT
