Sprint 1 — Scaffold: Typographic Resume (Pattern A)

Goal
- Create a minimal, deployable static homepage implementing the "Typographic Resume" direction (single-column lead summary, experience, projects, contact). The site must be static HTML/CSS with no JS dependency for core content.

Scope
In:
- A homepage with sections: About (lead), Experience, Projects, Contact
- Responsive CSS that becomes single-column on small screens
- Download link placeholder for `resume.pdf`

Out:
- No project detail pages or dynamic filters
- No deployment automation (deployment will be a separate sprint)

Tasks
1. Scaffold `index.html` with semantic sections.
2. Add `css/styles.css` with typographic scale and responsive rules.
3. Add `READ_ME.md` with local test and GitHub Pages notes.
4. Add `.nojekyll` to prevent Jekyll processing on GitHub Pages (file created separately).
5. Document acceptance criteria and verification steps in this file.

Files to touch
- [index.html](index.html)
- [css/styles.css](css/styles.css)
- [READ_ME.md](READ_ME.md)
- [.nojekyll](.nojekyll)

Acceptance Criteria (pass/fail)
- Index page loads in browser (pass/fail)
- Name and 1-line summary visible without scrolling on desktop (pass/fail)
- Headings use proper semantic tags (`h1`–`h3`) (pass/fail)
- Layout collapses to single column under 700px (pass/fail)
- Download resume link present and points to `resume.pdf` (pass/fail)
- No critical accessibility issues: skip link works, focus styles visible (pass/fail)
- No JS required to view core content (pass/fail)
- Body text contrast legible (pass/fail)
- Page served from local static server without errors (pass/fail)
- README includes GitHub Pages deployment note (pass/fail)

Verification steps
1. Open `index.html` in a desktop browser; confirm name+summary visible.
2. Resize window <700px and confirm layout stacks into single column.
3. View source to confirm semantic headings present.
4. Tab to verify skip link focus; try opening `resume.pdf` link (placeholder).
5. Run `python -m http.server 8000` and visit `http://localhost:8000/` — confirm no console JS errors.

Evidence / Receipts
- Files added to workspace: [index.html](index.html), [css/styles.css](css/styles.css), [READ_ME.md](READ_ME.md), [.nojekyll](.nojekyll)
- Assumptions documented: Choosing "Typographic Resume" direction (Pattern A). Minimal JS; system fonts.

Assumptions
- User accepts the recommendation from earlier to use the Typographic Resume direction (Pattern A) for Liyan.
- `resume.pdf` is a placeholder and not provided in this sprint.
