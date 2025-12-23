# Resume

A simple, static personal resume site built with HTML and CSS.

## Structure
- `data/profile.json` — source profile data.
- `templates/resume.json` — resume template and section order.
- `prompts/generate-resume.md` — content generation rules.
- `index.html` — rendered resume layout; pulls data from `data/profile.json`.
- `styles.css` — styling for the site.

## Run locally
Open `index.html` in a browser via a simple static server (for example: `python -m http.server 8000`) so the page can load `data/profile.json`.
