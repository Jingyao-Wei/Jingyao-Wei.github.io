# How to update your website

Every change deploys automatically ~2 minutes after you push to `main`
(or edit a file directly on github.com and commit).

## Add or edit papers
Edit `data/papers.yaml`. Each paper has a title, authors, status, abstract,
and optional `pdf` / `url` links. To host a PDF yourself, put it in
`static/papers/` and set `pdf: "/papers/filename.pdf"`.

## Update your bio
Edit `content/_index.md`.

## Add teaching
Edit `data/teaching.yaml`.

## Update your CV
Replace `static/files/cv.pdf` with the new file (keep the same name).

## Change your photo
Replace `static/images/photo.jpg` (square images look best).

## Change colors or fonts
Edit the variables at the top of `assets/css/main.css`.

## Contact details / tagline
Edit `hugo.toml` (the `[params]` section).
