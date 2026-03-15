# NYC Specifier List — Interactive Manager

A fully interactive contact database for managing NYC-area architecture and design firm specifiers. Built as a single-page web application with a polished Excel companion file.

## Live Demo

**[View the live app](https://YOUR_USERNAME.github.io/nyc-specifier-list/)**

## Features

- **Dashboard** — KPI cards, bar charts for firm type distribution, email coverage, geographic breakdown, and research status indicators
- **Contacts Table** — Searchable, sortable, and filterable table with pagination (1,191 contacts across 450 firms)
- **Firm Cards** — Visual card-based view grouped by firm, color-coded by type
- **CRUD Operations** — Add, edit, and delete contacts directly in the browser
- **CSV Export** — One-click export of filtered results
- **Responsive Design** — Works on desktop and tablet

## Firm Types

| Type | Count | Color |
|------|-------|-------|
| Architect | 310 firms | Blue |
| Lighting Designer | 68 firms | Yellow |
| Interior Designer | 52 firms | Green |
| Engineer | 12 firms | Orange |
| Landscape Architect | 8 firms | Pink |

## Files

- `index.html` — The full interactive web app (self-contained, no server needed)
- `Sample_Specifier_Portfolio.xlsx` — Formatted Excel workbook with 3 tabs (Specifier List, Contact Database, Dashboard)

## Tech Stack

- React 18 (CDN)
- Vanilla CSS (custom design system)
- No build tools required — single HTML file

## Setup

Just open `index.html` in a browser. No installation needed.

For GitHub Pages deployment, see instructions below.

## Deploy to GitHub Pages

1. Create a new repo on GitHub
2. Push this folder to the repo
3. Go to **Settings > Pages > Source > Deploy from branch > main**
4. Your site will be live at `https://YOUR_USERNAME.github.io/REPO_NAME/`
