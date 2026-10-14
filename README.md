# Rahul Golder — CV & Research

[Portfolio and CV](https://rg8420.github.io/cv/) · [Download PDF](https://rg8420.github.io/cv/Rahul_Golder_CV.pdf)

The canonical CV source is `Rahul_Golder_CV.tex`. GitHub Actions compiles it with XeLaTeX, then publishes the PDF and `site/index.html` to GitHub Pages. The source includes checks for a two-page CV and full-width project bullets.

## Updates

Edit `Rahul_Golder_CV.tex` and push to `main`. The **Build CV and publish portfolio** workflow regenerates the live PDF. To update the landing page, edit `site/index.html`.

GitHub Pages source: **GitHub Actions** (Settings → Pages).

For a separate GitHub.io portfolio, link to `https://rg8420.github.io/cv/`, or embed the PDF URL in that site's CV section.

## Local compilation

Run `latexmk -xelatex Rahul_Golder_CV.tex` using TeX Live with ModernCV installed.

Layout inspired by [bamos/cv](https://github.com/bamos/cv); content belongs to Rahul Golder.
