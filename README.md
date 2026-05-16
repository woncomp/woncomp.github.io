# woncomp.github.io

This repository contains the source for `https://woncomp.github.io`, a `Jekyll` blog using the `Chirpy` theme.

## Local development

Install dependencies:

```bash
bundle install
```

Start the local server:

```bash
bundle exec jekyll s
```

The site will be available at `http://127.0.0.1:4000`.

## Writing posts

Create new posts in `_posts/` using the filename format:

```text
YYYY-MM-DD-title.md
```

Each post should include front matter similar to:

```yaml
---
title: Post Title
date: 2026-05-16 10:00:00 +0800
categories: [notes]
tags: [jekyll, chirpy]
---
```

## Deployment

Deployment is handled by GitHub Pages through the workflow in `.github/workflows/pages-deploy.yml`.

Repository settings should use `Settings > Pages > Source: GitHub Actions`.
