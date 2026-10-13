# giovannitoto.github.io

Personal academic website of Giovanni Toto, published at https://giovannitoto.github.io/.

Built with [Jekyll](https://jekyllrb.com/) using the [AcademicPages](https://github.com/academicpages/academicpages.github.io) template.

## Structure

- `_pages/` — site pages (about, publications, presentations, CV, sitemap)
- `_data/navigation.yml` — top menu
- `_config.yml` — site settings and author profile
- `files/` — PDFs (CV, posters, slides)
- `images/` — profile photo and favicons

## Running locally

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```

The site is then served at http://localhost:4000 and rebuilds on change.
