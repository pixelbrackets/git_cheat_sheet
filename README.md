Build
=====

* Convert Markdown to HTML using https://gist.github.com/pixelbrackets/5046331
  * `./gfm2html git_cheat_sheet.md screen.css > index.html`
  * Remove unwanted whitespace: `<code>  ` → `<code>`
* Convert HTML to PDF using Chromium without page borders
  * `chromium index.html`
  * Save as git_cheat_sheet.pdf
* Push to Github
* Tag new release
