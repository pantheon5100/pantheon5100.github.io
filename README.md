# Kang Zhang's academic website

This site is based on [Jon Barron's academic website template](https://github.com/jonbarron/jonbarron_website).

## Adding a research note

Keep editable Markdown sources in `blog/`. Every public note should also have a matching static `.html` file in that folder so it opens both in local previews and on GitHub Pages without requiring a build step.

Use `blog/freeflow-eq8-to-eq9-derivation.html` as the article-page template, then add a matching card to the `Research Notes` section in `index.html`. For LaTeX, use `\(...\)` for inline equations and `\[...\]` for display equations in the generated HTML page.

The article template loads the bundled MathJax renderer and fonts from `blog/vendor/mathjax/`, so equations work in the local site without depending on an external CDN.
