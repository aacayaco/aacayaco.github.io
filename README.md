# [aacayaco.github.io](https://aacayaco.github.io)

Personal portfolio and blog site built with [MkDocs Material](https://squidfunk.github.io/mkdocs-material/).

## Development

Requires [uv](https://docs.astral.sh/uv/).

```bash
# Install dependencies
uv sync

# Serve locally with live reload
uv run mkdocs serve
```

Open [http://127.0.0.1:8000](http://127.0.0.1:8000) in your browser.

## Deployment

Pushes to `master` automatically deploy to GitHub Pages via GitHub Actions.

To deploy manually:

```bash
uv run mkdocs gh-deploy
```

## Structure

```
docs/           # Site content (Markdown)
  index.md      # Home page
  about.md      # About page
  posts/        # Blog posts
mkdocs.yml      # MkDocs configuration
pyproject.toml  # Python project + dependencies
.github/
  workflows/
    deploy.yml  # GitHub Actions deploy workflow
```
