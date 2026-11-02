# Shayan Mirkhani — portfolio

- `index.html`  — main page (monochrome design): hero, about, skills, resume, works (with category filter), contact, A4/PDF resume.
- `cyber.html`  — the cyberpunk page ("Cyber Sanctum"). Reached from the ⚡ button on the main page; its ⚡ button leads back.
- Works categories: edit the last value of each row in the `WK` array in `index.html` (`store` / `corp`); chips and counts update on their own. New category = add it to `WCAT`, add `c_<name>` texts in `Object.assign(D.en/D.fa, ...)`.
- A4 resume: built from the same data as the page (`a4html()`), printed with `window.print()` → "Save as PDF".
