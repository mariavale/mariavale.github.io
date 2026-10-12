# mariavale.github.io

Personal academic site. Plain HTML and CSS, no build step.

## Files

- `index.html` — all page content
- `style.css` — all styling (colors are the variables at the top)
- `headshot.jpg` — profile photo (square, about 480px)
- `cv.pdf` — linked from the header; replace with your current CV, keeping the filename
- `favicon.svg` — browser tab icon

## Common edits

- **Add a paper:** copy one `<li>` block inside `<ul class="pubs">` and edit it. The `data-tags` attribute controls the filter buttons: use any of `first`, `nlp`, `cogsci`, separated by spaces.
- **Add news:** add a line at the top of `<ul class="news">`. Keep it to the five or six most recent items.
- **Update the date:** change "Last updated" in the footer.

## Publishing

Replace the old files in the repo with these, then commit and push. GitHub Pages republishes automatically within a minute or two.
