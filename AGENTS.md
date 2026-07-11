# Plain static site — keep it that way

This is a hand-written HTML/CSS site with no build step, no package.json, and no framework. Do not introduce Node tooling, bundlers, or frameworks. Edit `index.html` and `css/main.css` directly.

Style notes:

- One page, one stylesheet. Keep the site short — the project is in its planning stage.
- Aesthetic: airport departure board, not game village. Restrained palette (background + amber accent), monospace for board/headings, wabi-sabi restraint.
- Support light and dark via `light-dark()`; the status board panel is always dark.
- Sibling reference for structure/conventions: https://github.com/SudoSodokuApp/SudoSodokuApp.github.io
