# My personal website

I designed this website using the Jekyll theme [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose. I got started with the Minimal Mistakes [starter template](https://github.com/mmistakes/mm-github-pages-starter).

## Customizations

I made the following custom changes to the original theme:

- Modified `_data/ui-text.yml` and `_includes/author-profile.html` to change Follow Label from "Follow" to "Connect."
- Modified `_includes/author-profile.html` to allow author bio links in sidebar to open in new tab, toggled by `new_tab`.
- Modified `_includes/footer.html` to allow Follow Label in footer to be hidden (toggled by `hide_follow_label`).
- Modified `_includes/masthead.html` to allow website title to be hidden (toggled by `hide_title`) and allow links in navigation menu to open in new tab (toggled by `new_tab`).
- Added `_layouts/single-alt-title.html` to create variation of Single layout with `alt_title` field, so title in text can be different from title of page.
- Modified `assets/css/main.scss` to make the following changes:
	- Adjust font size everywhere.
	- Adjust width of left and right sidebars.
	- Adjust opacity of sidebar.
	- Adjust size, shape, and border of profile picture in sidebar.
	- Adjust font size of author name in sidebar.
	- Add `color-inherit` class for use with icons.
- Deleted `index.html` ("About" page serves as home page instead).
- Added `pdfjs-4.8.69-dist`, which contains the JavaScript library [PDF.js](https://mozilla.github.io/pdf.js/), to render PDFs.
