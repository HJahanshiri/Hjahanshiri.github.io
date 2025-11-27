# Noah's Blog

A minimal, Paul Graham-inspired personal blog built with Jekyll and GitHub Pages.

## Adding New Content

### Essays (Long-form explorations)
Create a new file in `_essays/` with the format: `YYYY-MM-DD-title.md`

Example: `_essays/2025-11-27-first-principles.md`

```markdown
---
title: "First Principles: Engineering Your Life"
date: 2025-11-27
---

Your essay content here...
```

### Log (Quick thoughts)
Create a new file in `_log/` with the format: `YYYY-MM-DD-title.md`

Example: `_log/2025-11-27-quick-thought.md`

### Posts (Technical guides)
Create a new file in `_posts/` with the format: `YYYY-MM-DD-title.md`

Example: `_posts/2025-11-27-how-to-guide.md`

## Local Development

```bash
bundle install
bundle exec jekyll serve
```

Visit `http://localhost:4000` to preview.

## Publishing

Just commit and push to GitHub. GitHub Pages will automatically build and deploy your site.

```bash
git add .
git commit -m "Add new essay"
git push
```

