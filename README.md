# zeppombal.github.io

Source of [zeppombal.github.io](https://zeppombal.github.io), built by GitHub Pages with Jekyll.

- `index.md`: bio and news. News is a markdown list under `## News`. Start each item with its date in bold (`- **Oct 2026** ...`), and keep the `{: .news}` line right after the last item.
- `_data/publications.yml`: selected publications, newest first.
- `_config.yml`: name, role, links and photo.
- `_layouts/homepage.html`, `_includes/publications.html` and `assets/css/main.css`: page structure and styles.

Preview locally with `bundle install && bundle exec jekyll serve`.
