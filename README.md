Build
=====

* Convert Markdown to HTML using https://gist.github.com/pixelbrackets/5046331
  * `./gfm2html git_cheat_sheet.md screen.css > index.html`
  * Remove unwanted whitespace: `<code>  ` → `<code>`
  * Remove nofollow directive: ` rel="nofollow"` → ` `
  * Insert OpenGraph metatags

        <meta name="description" content="A comprehensive cheat sheet for daily work with Git" />
        <meta property="og:type" content="website" />
        <meta property="og:site_name" content="Git Cheat Sheet" />
        <meta property="og:title" content="Git Cheat Sheet" />
        <meta property="og:description" content="A comprehensive cheat sheet for daily work with Git" />
        <meta property="og:image" content="https://pixelbrackets.github.io/git_cheat_sheet/card.png" />
        <meta name="twitter:card" content="summary" />
        <meta name="twitter:site" content="@pixelbrackets" />
        <meta name="twitter:title" content="Git Cheat Sheet" />
        <meta name="twitter:description" content="A comprehensive cheat sheet for daily work with Git" />
        <meta name="twitter:image" content="https://pixelbrackets.github.io/git_cheat_sheet/card.png" />

* Convert HTML to PDF using Chromium without page borders
  * `chromium index.html`
  * Save as git_cheat_sheet.pdf
* Push to Github
* Tag new release
