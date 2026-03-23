# learn2read

This repo contains a small, static HTML tool for Chinese character recognition practice (optimized for iPad).

## Folder structure

- `docs/`: deployable static site
  - `docs/index.html`: the tool UI
  - `docs/data/books.json`: book list + focus characters (edit this to refresh content)
- `books_screenshot/`, `processed/`: local-only scratch data (ignored by git)

## Update workflow

1. Edit `docs/index.html` and/or `docs/data/books.json`
2. Commit and push
3. Your hosted URL updates automatically (GitHub Pages / Netlify / Cloudflare Pages)

## GitHub Pages (simple option)

If you use GitHub Pages, configure it to serve from the `docs/` folder on your default branch.

