# StellaZhangUCI.github.io

The public site for the **UCI New Venture Competition Archive**.

Live: [stellazhanguci.github.io](https://stellazhanguci.github.io/)

## What this is

A citation-backed historical record of UCI's Stella Zhang New Venture Competition (2009 to 2026). Year-by-year awards, team rosters, post-competition outcomes, cross-year analytics.

## Built with

Plain Jekyll. No build step locally. GitHub Pages compiles on push.

- `_config.yml` – site config and the `years` collection.
- `_data/` – the verified data files copied from the companion repo.
- `_layouts/` – `default.html` and `year.html`.
- `_years/` – one stub per year (2009 to 2026). The layout reads data and renders.
- `assets/css/main.css` – classic academic stylesheet.

## Data source

All claims trace back to the companion repository:

[github.com/StellaZhangUCI/History](https://github.com/StellaZhangUCI/History)

If you spot something wrong, open a pull request against the data files in that repo. The site rebuilds itself once the data here is updated.

## Local preview

Optional. The site builds automatically on push, so this is only useful if you want to preview a change before pushing.

```
bundle install
bundle exec jekyll serve
```
