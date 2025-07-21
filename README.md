# My Jekyll Site

Welcome to my basic [Jekyll](https://jekyllrb.com) project! This site is built using the Jekyll static site generator and is ready to deploy on GitHub Pages or any static host.

## 🔧 Project Structure

```
.
├── _config.yml       # Main config file
├── _posts/           # Blog posts in Markdown format
├── _layouts/         # HTML templates
├── _includes/        # Partial includes
├── _sass/            # Custom SASS styles
├── assets/           # CSS, JS, images
├── index.md          # Home page
└── _site/            # Generated site (auto-generated)
```

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

- [Ruby](https://www.ruby-lang.org/en/)
- [Bundler](https://bundler.io/)
- [Jekyll](https://jekyllrb.com/)

Install Jekyll and Bundler (if not already):

```bash
gem install bundler jekyll
```

### Install Dependencies

```bash
bundle install
```

### Run the Site Locally

```bash
bundle exec jekyll serve
```

Then open your browser and go to:

```
http://localhost:4000
```

## 🛠 Configuration

Edit `_config.yml` to update your site’s title, description, base URL, and other settings.

Example:

```yaml
title: My Jekyll Site
description: A simple static site built with Jekyll.
baseurl: "" # leave blank for root
url: "https://yourusername.github.io"
```

## ✍️ Writing Posts

Create a Markdown file in the `_posts/` folder using the format:

```
YEAR-MONTH-DAY-title.md
```

Example:

```
2025-07-21-welcome-to-jekyll.md
```

Include YAML front matter:

```markdown
---
layout: post
title: "Welcome to Jekyll"
date: 2025-07-21
categories: blog
---
```

## 📦 Deployment

To deploy to GitHub Pages:

1. Push to the `main` branch of your repo.
2. Enable GitHub Pages in the repository settings.
3. Set the source to the `docs` folder or the `gh-pages` branch (or `_site` with a separate deployment workflow).

Or use a static host like Netlify, Vercel, or Cloudflare Pages.

## 🧾 License

This project is licensed under the [MIT License](LICENSE).

---

