# yunbolyu.github.io

Personal academic homepage of [Yunbo Lyu](https://yunbolyu.github.io), Ph.D. candidate at Singapore Management University.

Pure static HTML + CSS — no Jekyll, no build step. Design inspired by [Jon Barron](https://jonbarron.info/).

## Preview locally

```bash
python3 -m http.server 8000
```

Open http://localhost:8000 in a browser. Any edits to `index.html` show up on refresh.

Alternatively, double-click `index.html` (relative paths for images / PDFs still resolve as long as the files sit alongside it).

## Deploy

Push to `main` — GitHub Pages serves `index.html` directly. `.nojekyll` is present so no Jekyll processing happens.

## File layout

```
.
├── index.html          # the whole site: bio, news, publications, talks, awards, services
├── index_old.html      # the previous (Chirpy) homepage, kept as backup
├── yunbo_new.png       # profile photo
├── smu.png             # SMU logo (nav bar)
├── talk/               # slide PDFs linked from Invited Talks
├── .nojekyll           # disables GitHub Pages Jekyll processing
└── _config.yml, _tabs/, Gemfile, ...   # leftover Chirpy scaffolding — not used
```

## Editing tips

- **Add a publication**: append a `<li>` in the `Publications` `<ol class="pubs">` in `index.html`. The numbering (`1.`, `2.`, …) continues automatically via CSS counters across both Publications and Preprints.
- **Add a news item**: add a `<li>` to `<ul class="news">`. The top 5 are shown by default; older items go inside `<details class="news-more">` which collapses by default.
- **Change the photo**: replace `yunbo_new.png`, or tweak `background-position` / `background-size` on the `.profile` div (HEADER section) to re-crop.
- **Nav width / colors / fonts**: all CSS lives inline in the `<style>` block at the top of `index.html`.

## License

Content (text, photos) © Yunbo Lyu. Feel free to use the HTML/CSS structure as a template for your own page.
