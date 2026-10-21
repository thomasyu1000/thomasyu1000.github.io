Personal website, built with [Jekyll](https://jekyllrb.com) and the [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) theme. I got started with the Minimal Mistakes [starter template](https://github.com/mmistakes/mm-github-pages-starter).

Beyond the theme's settings, I made the following customizations:

- Modified `_config.yml` to remove settings the site does not use, and to disable the GitHub Pages plugin `titles_from_headings` so the page's heading is not also rendered as a title.
- Modified `assets/css/main.scss` to make the following changes:
  - Adjust font sizes.
  - Reduce the space to the right of the text.
  - Scroll smoothly to sections of the page.
  - Format buttons and abstract toggles.
  - Do not fade the sidebar, and make the photo and name not clickable.
  - Adjust size and shape of profile picture.
  - Space photo, name, and email evenly, and on mobile show email instead of hiding it behind a button.
  - Adjust relative font sizes of name, email, and copyright line.
- Added `_pages/home.md`, a single page served at `/`, using `<details>` for collapsible abstracts and buttons for links.
- In `_data/navigation.yml`, bolded the links with HTML in their titles.
- Added `CNAME` for the custom domain, and `favicon.ico` and `apple-touch-icon.png`.
- Modified `Gemfile` to keep only `github-pages`.
- Modified `.gitignore` to ignore `.DS_Store`.

To update the theme, change `remote_theme` in `_config.yml`.
