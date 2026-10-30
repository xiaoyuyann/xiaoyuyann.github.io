# Xiaoyu Yan - Personal Homepage

Static site served by GitHub Pages. No build step.

## Files
- `index.html` : the whole page (styles and scripts inline)
- `assets/portrait.jpg` : web-sized portrait used on the page (720x900)
- `assets/resume.pdf` : resume linked from the page (`cv.pdf` and `assets/cv.pdf` are copies so old links still work)
- `avatar.jpg`, `assets/avatar.jpg` : original full-size photo
- `_archive/` : previous version of the page and CV (Jekyll does not publish folders starting with `_`)

## Updating
- News: edit the `<ul class="news">` list near the top of `index.html`.
- Publications: copy one `<li class="pub">` block; give it a unique `id` and BibTeX `id`.
- Education: one `<li>` per degree in `<ul class="degrees">`.
- Experience: each `<li class="stop">` is one organization. Add the class `transfer` when it holds several roles.
