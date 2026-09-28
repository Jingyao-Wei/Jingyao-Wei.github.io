# How to update your website

The root of the GitHub repository holds the built site; this `source/`
folder holds the Hugo project it is generated from. The easiest way to
update is to ask Claude for the change and upload the refreshed files.

## Add or edit papers
Edit `data/papers.yaml`. Each paper has a title, authors, status, abstract,
and optional `pdf` / `url` / `coverage` links. To host a PDF yourself, put
it in `static/papers/` and set `pdf: "/papers/filename.pdf"`.

## Update your bio
Edit `content/_index.md`.

## Add teaching or presentations
Edit `data/teaching.yaml` or `data/presentations.yaml`.

## Update your CV
Replace `static/files/cv.pdf` with the new file (keep the same name).

## Change your photo
Replace `static/images/photo.jpg` (square images look best).

## Change colors or fonts
Edit the variables at the top of `assets/css/main.css`.

## Contact details / tagline
Edit `hugo.toml` (the `[params]` section).

## Rebuild
Install Hugo (extended), run `hugo --gc --minify` inside `source/`, and copy
the contents of `public/` to the repository root.
