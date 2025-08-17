# alterhuman.org.uk

Website for alterhuman.org.uk

## Local development

- Prereqs: Ruby + Bundler + Jekyll
- Run: `jekyll serve` (or `bundle exec jekyll serve` if using a Gemfile)
- Open: http://localhost:4000

## Structure

- `_layouts/default.html`: Site layout with header and nav
- `_includes/head.html`, `_includes/nav.html`: Shared head + navigation
- `_blog/`: Blog collection items (output to `/blog/:name/`)
- `blog/index.html`: Lists items from the blog collection

Static assets remain at existing paths (e.g. `/style.css`, `/img/...`).
