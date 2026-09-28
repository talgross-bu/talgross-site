# Tal Gross — personal website

Plain HTML/CSS site served by GitHub Pages. No build step.

- **Edit:** change `index.html` (home page) or `problem-sets.html`. Styles live in `style.css`. To add a paper, copy an existing `<div class="paper">` block.
- **Files:** put new PDFs in `papers/` (research) or `teaching/`; the CV is `talgross_cv.pdf` at the top level.
- **Preview locally:** `python3 -m http.server 8765`, then open http://localhost:8765.
- **Publish:** `git add -A && git commit -m "Describe change" && git push`. The live site updates in about a minute.
