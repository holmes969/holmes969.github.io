# Content Guide

This site is an al-folio Jekyll site. Most routine updates are plain text edits.

## Add a Publication

1. Copy `_templates/publication.bib`.
2. Paste it into `_bibliography/papers.bib`.
3. Replace the title, authors, venue, year, and links.
4. Optional: add a thumbnail image to `assets/img/publication_preview/` and set `preview` to just the filename.
5. Optional: set `selected = {true}` to show the paper on the homepage.

Supported publication button fields:

- `pdf`: PDF URL or filename in `assets/pdf/`
- `html`: paper page URL
- `website`: project page URL
- `code`: code URL
- `video`: video URL
- `slides`: slides URL or filename in `assets/pdf/`
- `poster`: poster URL or filename in `assets/pdf/`
- `supp`: supplement URL or filename in `assets/pdf/`

For a not-yet-known link, use `website = {#todo-replace-with-paper-or-project-url}` so it is easy to search later.

## Add News

Edit `_data/news.yml`. Copy `_templates/news.yml` if you want a starter entry.

Each item has this shape:

```yaml
- date: "YYYY-MM-DD"
  text: Short news item with optional [link](https://example.com/).
```

The homepage automatically sorts news by date, newest first.

## Update the CV PDF

The website links directly to `assets/pdf/cv.pdf`. Replace that file when the PDF changes.

## Preview Locally

Use a modern Ruby version supported by al-folio, then run:

```bash
bundle install
bundle exec jekyll serve
```

Open the printed local URL and check `/`, `/publications/`, and the CV PDF link.
