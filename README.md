# Recipes

A small family recipe collection, published at
**https://gatoravi.github.io/recipes**.

It's a plain [Jekyll](https://jekyllrb.com) site — GitHub Pages builds it
automatically from the `gh-pages` branch, so there's no build step to run and
no GitHub Action to maintain.

## Adding a recipe

Create a Markdown file in `_posts/` named `YYYY-MM-DD-title.md`:

```markdown
---
layout: post
title: "Tomato rice"
categories: blog        # or: notebook
tags: [rice, lunch]
date: 2026-10-04
---

## Ingredients

- ...

## Method

1. ...
```

That's it — commit and push, and the new recipe appears on the home page.

## Structure

- `_posts/` — one Markdown file per recipe
- `_layouts/` — `default`, `page`, `post`
- `_includes/` — `head`, `header`, `footer`
- `assets/css/style.css` — the whole stylesheet (plain CSS, light + dark)
- `notebook/` — the "Mom's notebook" page and scan gallery
- `recipe_images/notebook/` — web-sized page scans
- `assets/notebook/` — the full-resolution scans PDF

## Local preview (optional)

```bash
bundle install
bundle exec jekyll serve
```
