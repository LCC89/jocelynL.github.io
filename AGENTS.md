# AGENTS.md

## Cursor Cloud specific instructions

This is a **static GitHub Pages site** (`jocelynL.github.io`) consisting of a single `index.html` page. There is no build system, no package manager, no dependencies, no tests, and no linter configured.

### Running the dev server

```bash
cd /workspace && python3 -m http.server 8080
```

Then open `http://localhost:8080/` in a browser.

### Known issues

- The HTML references `styles/style.css`, `scripts/main.js`, and `images/DSC00442.png` which are **not present** in the repository. The page renders but these assets will 404.
- There is no automated test suite or linter configured for this project.
