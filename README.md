<p align="center"><img src="https://raw.githubusercontent.com/go-ruby-webrick/brand/main/social/go-ruby-webrick.png" alt="go-ruby-webrick/go-ruby-webrick.github.io" width="720"></p>

# go-ruby-webrick.github.io

The organization's institutional landing page, served at
<https://go-ruby-webrick.github.io> and built with [Hugo](https://gohugo.io). It is a
single page (custom `layouts/index.html`).

Documentation lives in a separate repository,
[go-ruby-webrick/docs](https://github.com/go-ruby-webrick/docs), served at
<https://go-ruby-webrick.github.io/docs/>. This page links there.

`.github/workflows/deploy-pages.yml` builds the landing with Hugo and deploys it
to GitHub Pages on every push to `main`.

## Local preview

```bash
hugo server      # http://localhost:1313
```
