# vineelp.com

Personal site, built with Jekyll and served by GitHub Pages (no theme, no plugins).

## Edit content

- **Projects:** `_data/projects.yml`. Leave a link `""` to hide it; `group: true` labels a group project; `featured: true` puts it on the home page.
- **Menu:** `_data/nav.yml`. Each page shows its own item first, then the rest in loop order.
- **Links (CV, GitHub, LinkedIn, email):** `_config.yml` under `links`.
- **CV:** replace `resume.pdf`.
- **Photo:** `assets/img/headshot.jpg` (square).
- **Styles:** `assets/css/site.css`.

## Preview locally

```sh
bundle install          # first time only
bundle exec jekyll serve
```

Then open http://localhost:4000.
