# Muhammad Sufyan — Personal Website

Static site (HTML/CSS, no build step). Works anywhere.

## Files
- `index.html` — Home
- `research.html` — Research & Experience
- `projects.html` — Projects index
- `project-*.html` — One page per project
- `cv.html` — CV & Contact
- `styles.css` — Shared styling
- `assets/` — photo + CV PDF

## Deploy on GitHub Pages (recommended)
1. Create a new **public** repo named exactly: `mesufyan.github.io`
2. Upload every file here (keep the `assets/` folder).
3. Repo **Settings → Pages → Build from branch → main → /(root) → Save**.
4. Live in ~1 min at: https://mesufyan.github.io

## Or deploy on Netlify (no Git)
1. Go to app.netlify.com → "Add new site" → "Deploy manually".
2. Drag this whole folder onto the page. Done.

## Adding a project's GitHub link later
Open the project file (e.g. `project-digitaltwins.html`), find:
    <span class="repo soon">Repository coming soon</span>
and replace it with:
    <a class="repo" href="https://github.com/mesufyan/REPO-NAME">&#9733; View repository</a>
The same swap works in `projects.html` for the card.
