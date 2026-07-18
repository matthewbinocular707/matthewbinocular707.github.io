# kumarM6.github.io

Personal portfolio for **Mohit Kumar** — Product Manager (Security & AI).
Hand-built static site (HTML/CSS/JS, no build step), hosted free on GitHub Pages.

**Live URL (once published):** https://kumarm6.github.io

## Structure
```
index.html            Home — intro + project list + writings/blogroll teasers
about.html            Long-form about
projects/             One detail page per project
  epm.html            CIEM 0→1 launch
  sse.html            Security Service Edge preview
  sentinel-secops.html  Unified SecOps transition guidance
  sentinel-mcp.html   AI-native SIEM via MCP
  mdash.html          Multi-model AI vulnerability scanner (preview)
  gemba-walk.html     "Gemba Walk" partner research methodology
writings/index.html   Blog landing (placeholder, ready for posts)
blogroll.html         Curated external links
css/styles.css        Theme (light/dark), typography, layout
js/main.js            Theme toggle + nav
assets/img/           favicon
.nojekyll             Serve files as-is (no Jekyll processing)
```

## Local preview
No build step needed. From the repo root:
```powershell
python -m http.server 8080
# then open http://localhost:8080
```

## Editing content
- **Add a project:** copy a file in `projects/`, edit the content, and add a `<li>` to the project list in `index.html`.
- **Add a writing:** add an HTML file under `writings/` and a row in `writings/index.html`.
- **Theme/colors:** edit the CSS variables at the top of `css/styles.css`.

## Before going live — TODO
Search-and-replace these placeholders:
- `REPLACE_ME@example.com` → your public email
- `https://www.linkedin.com/in/REPLACE_ME` → your LinkedIn URL

## Publishing (GitHub Pages user site)
1. Create a **personal** GitHub repo named exactly `kumarM6.github.io`.
2. Push this folder to the `main` branch.
3. In repo **Settings → Pages**, set source to `main` / root.
4. Site serves at `https://kumarm6.github.io`.

> Note: a GitHub **user site** only serves at the root domain when the repo name
> matches your username. This repo assumes the personal username `kumarM6`.

## Content note
All content is generalized and public-safe: no customer names, deal values, internal
codenames, or confidential metrics.
