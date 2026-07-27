# demo

Hand made website previews, one folder per prospect, served by GitHub Pages
at `https://coodiestudio.github.io/demo/<slug>/`.

Each preview is self contained: `index.html`, `assets/style.css`,
`assets/img/`. Nothing here reads from a database or an API.

Every page carries `<meta name="robots" content="noindex, nofollow">`.
The photographs belong to the prospect the preview is built for, so the
pages must stay out of search results.

To add one: copy a folder, swap the images and the copy, adjust the two
colours in `:root`, commit, push.
