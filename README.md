# Library Tutorials

Accessible, browser-based library instruction tutorials built as single-file HTML pages.

## Overview

This repository contains interactive tutorials designed for higher education learners.  
Each tutorial is self-contained (no build step, no external dependencies) and can run in any modern web browser.

## Project Goals

- Provide clear, engaging instruction for library information literacy topics
- Keep tutorials easy to edit and maintain
- Ensure strong accessibility and keyboard usability
- Support simple hosting with GitHub Pages

## Repository Structure

- `*.html` — Individual tutorial files (one tutorial per file)
- `AGENTS` — Authoring guidance, standards, and accessibility requirements

## Current Tutorials

| File | Topic | Status |
|---|---|---|
| `popular-scholarly-trade.html` | Distinguishing popular, scholarly, and trade articles | ✅ Complete |

## Accessibility

Tutorials in this project are expected to align with **WCAG 2.1 Level AA** standards, including:

- Semantic heading structure
- Keyboard-accessible interactions
- Visible focus states
- Sufficient color contrast
- Non-color indicators for meaning
- Accessible alternatives for drag-and-drop interactions

See `AGENTS` for full implementation requirements.

## Local Use

No setup required:

1. Clone or download this repository
2. Open any tutorial `.html` file in your browser

## GitHub Pages

Tutorials can be published via GitHub Pages. Typical URL format:

`https://[username].github.io/[repository-name]/[filename].html`

For this repository, that will typically be:

`https://pamelanmartin.github.io/tutorials/[filename].html`

## Contributing

Contributions are welcome. When proposing updates:

- Keep each tutorial self-contained in a single HTML file
- Preserve accessibility expectations
- Use clear commit messages describing instructional and UX changes

## License

Add your preferred license here (for example, MIT, CC BY, or institutional guidance).
