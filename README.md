# Resume Builder

A lightweight, browser-based tool for assembling targeted resume versions quickly and deliberately.

**[Live Demo →](https://schema-syntax.github.io/Resume-Builder/)**

---

## Why I Built This

Different roles call for different resume versions. Maintaining multiple documents is error-prone, and editing under application pressure is worse. This tool makes resume customization fast, repeatable, and intentional — select a summary track, check the bullets that fit the role, reorder by priority, and copy the plain-text output directly into your document editor.

## How It Works

- Choose a **summary track** (e.g. Data Analyst, Operations Analyst, Research & Reporting)
- **Check bullets** from each role — track tags show which bullets suit which track
- **Drag to reorder** selected bullets within each role
- **Search** to filter bullets by keyword
- Toggle optional sections (certifications, additional experience)
- **Copy output** — plain text, ready to paste into Pages, Word, or any editor

## Structure

| File | Purpose |
|------|---------|
| `portfolio.html` | Self-contained demo with fictional data — this is what's deployed |
| `index.html` | Personal offline version (not included — contains real resume data) |
| `resume-data.js` | Content layer for the offline version (not included — personal data) |

The offline version separates content (`resume-data.js`) from the app (`index.html`), so resume content can be edited without touching application logic. The demo version bakes fictional data directly into a single file for easy deployment.

## Stack

Plain HTML, CSS, and vanilla JavaScript. No frameworks, no build step, no dependencies. Opens in any browser locally or deploys to GitHub Pages as a static file.

---

*Demo data is entirely fictional.*
