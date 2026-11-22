# YA! Agency portfolio

The deployable website is `index.html` at the repository root. It is a self-contained static page, with the two local font files at the repository root (`space-grotesk.ttf` and `syne.ttf`).

`ya-agency-source.zip` contains the editable source files from the project (`src/App.tsx`, `src/YaMark.tsx`, `src/main.tsx`, `src/style.css`, and source assets). The React entry points use the Instinct Files runtime (`@instinct/files`); GitHub Pages serves the generated static `index.html` and does not need that runtime.

For a site change, update the editable source and the deployable `index.html`, then commit both to `main`. Keep any new public assets alongside the page and reference them with repository-relative paths.
