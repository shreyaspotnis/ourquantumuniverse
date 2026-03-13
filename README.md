# Our Quantum Universe

A static blog built with [Hugo](https://gohugo.io/) and deployed to GitHub Pages. Supports LaTeX-style math equations via [KaTeX](https://katex.org/).

## Writing Posts

Add a new markdown file in `content/posts/`:

```markdown
---
title: "Your Post Title"
date: 2026-03-13
math: true
---

Your content here. Use $E = mc^2$ for inline math
and display blocks:

$$\int_0^\infty e^{-x^2} dx = \frac{\sqrt{\pi}}{2}$$
```

Set `math: true` in the front matter to enable equation rendering.

## Local Development

Install [Hugo](https://gohugo.io/installation/) (v0.132+), then:

```bash
hugo server
```

Visit `http://localhost:1313/ourquantumuniverse/` to preview.

## Deployment

The site is automatically built and deployed to GitHub Pages when changes are pushed to the `main` branch.

**Setup**: In the repository settings, go to Pages and set the source to "GitHub Actions".
