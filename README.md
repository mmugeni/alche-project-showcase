# Div Soup Activity — ALCHE Software Engineering Student Project Showcase

## Context
You are given a fictional ALCHE Mauritius Software Engineering student project showcase. The page welcomes projects from **all current specialisations**: Full-Stack Web Development, Low-Level Programming, AR/VR, and Machine Learning. All project descriptions are **teaching examples**, not claims about actual student work.

## Student task
Refactor `index.html` into **`index.semantic.html`**. Keep the same page content, links, logo, image, and optional stylesheet. The starter deliberately contains generic `<div>` wrappers; do not simply replace every `<div>` indiscriminately.

1. Choose semantic elements where appropriate: `header`, `nav`, `main`, `article`, `section`, `aside`, `footer`.
2. Replace `.title` blocks with logically ordered `h1`–`h6` headings (do not skip heading levels).
3. Express `.meta` appropriately with `p`, `time` (using `datetime` where appropriate) or other relevant inline elements.
4. Convert `.image` into a `figure` with `figcaption`; preserve the meaningful image `alt` text.
5. Convert `.quote` into a `blockquote` (optionally with a citation).
6. Convert `.related` into a suitably named section with a heading and a list. Use one consistent structure for related links: `ul > li > article` OR `ul > li > a`.
7. Refactor `.cards` and `.card` into meaningful `section`, `article`, and/or list groupings.
8. Make the sidebar an `aside` and give the search input a real associated `label`, not just a placeholder.
9. Include **exactly one** `main`; preserve the skip link so it targets `#main`.
10. Give navigational landmarks accessible names where needed, such as `aria-label="Primary"`.

## Deliverable
Submit **`index.semantic.html`** through Canvas, including supporting assets only if your instructor asks for them. No completed solution is provided.

## CSS
`styles.css` is for optional visual reference only. **CSS is not required or assessed.** The search button is illustrative; adding JavaScript search behavior is not required.

## Files
- `index.html` — starter HTML (intentionally non-semantic)
- `styles.css` — optional existing CSS
- `alche-logo.png` — previously supplied ALCHE logo
- `project-showcase.svg` — local sample illustration
- `README.md` — instructions
