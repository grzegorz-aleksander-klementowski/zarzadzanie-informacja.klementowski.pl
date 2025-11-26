# Information Management Klementowski Website

Static portfolio site presenting the "Klementowski Information Management" services: BPM consulting, information-flow optimization, business mapping, search visibility, SQL/data efficiency, secure Rust blockchain apps, and AI adoption. The homepage features a video hero, smooth-scrolling navigation, animated section reveals, and contact details for quick collaboration.

## Repository structure
- `index.html` – main landing page with hero, services grid, competencies, and contact sections.
- `ai-apps.html`, `airtrails-sql-queries.html`, `blockchain-apps.html`, `games-projects.html`, `google-serp-seo-comparison-tool.html`, `php-sql-project.html` – standalone project write-ups linked from the portfolio tiles.
- `css/` – shared styling (layout, navigation, animations, responsive tweaks, footer, and page-specific styles).
- `javascript/script.js` – interactive behaviors (typewriter hero text, hamburger menu, smooth scroll, section reveal observer, and touch/mouse scroll helpers).
- `img/`, `icons/`, `fonts/`, `vid/` – static assets used across the pages.
- `CNAME` – preserves the custom domain for GitHub Pages deployments.

## Running locally
1. Install any simple static server (Python is built-in on most systems).
2. From the repository root, start a server, e.g. `python -m http.server 8000`.
3. Visit `http://localhost:8000/index.html` to browse the site; linked subpages share the same asset paths.

## Deployment tips
- Keep `CNAME` committed so the custom domain continues working when publishing via GitHub Pages.
- All assets use relative paths, so the site works from any static host without build steps.

## Contributing
Feel free to open issues or PRs for content edits, accessibility improvements, or layout refinements. Please keep markup semantic and avoid adding heavy dependencies to maintain a lightweight, static footprint.

## License
Licensed under the GNU General Public License v3.0. See `LICENSE` for details.

