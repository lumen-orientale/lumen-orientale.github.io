# Lumen Orientale

An English-language journal about noticing more: thoughtful notes on creativity,
everyday rituals, places, and the small details that give ordinary days their
light. Built with Hugo, the Blowfish theme, and Markdown.

## Run locally

Install [Hugo Extended](https://gohugo.io/installation/) 0.167.0, then run:

```sh
hugo server
```

The Blowfish theme is included as a Git submodule. If you have just cloned this
repository, initialize the theme with `git submodule update --init --recursive`.
Open the local address printed by Hugo to preview the site.

## Publish

The included GitHub Actions workflow builds the site and deploys it to GitHub
Pages whenever changes are pushed to `main`. In the repository settings, set
**Pages → Build and deployment → Source** to **GitHub Actions**.

Add new articles as Markdown files under `content/posts/`. For example:

```sh
hugo new content posts/my-new-article.md
```

## Customize

- Site title, language, and URLs: `config/_default/hugo.toml`
- Blowfish appearance and author details: `config/_default/params.toml`
- Navigation: `config/_default/menus.en.toml`
- Homepage: `content/_index.md`
- Homepage background: `static/img/fssp-urbe.jpg` and `assets/css/custom.css`
- About page: `content/about/index.md`
