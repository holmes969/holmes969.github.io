# Cheng Zhang Personal Website

This repository builds https://holmes969.github.io with the al-folio Jekyll theme.

Routine content edits are documented in [CONTENT_GUIDE.md](CONTENT_GUIDE.md):

- publications: `_bibliography/papers.bib`
- publication images: `assets/img/publication_preview/`
- news: `_news/`
- downloadable CV PDF: `assets/pdf/cv.pdf`

Deployment is handled by `.github/workflows/deploy.yml`, which builds the site and publishes `_site` to the `gh-pages` branch.
