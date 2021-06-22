# My Résumé
This repository contains a résumé written in LaTeX. It is mainly posted for my personal use.

The LaTeX code itself is based off of the (heavily modified) [Professional CV](https://www.sharelatex.com/templates/cv-or-resume/professional-cv) template by Alessandro Plasmati.

Note: the .pdf file in this repo may or may not be up to date with the .tex code; it's just a reference for convenience.

## Dependencies
 * LaTeX itself, along with the following packages: `fontspec`, `geometry`, `parskip`, `titlesec`, `hyperref`
 * The Fontin font family from the [exljbris Font Foundry](https://www.exljbris.com/fontin.html)
 * Font Awesome from their [website](http://fontawesome.io/)

## Build

The build requires xelatex (because of the `fontspec` dependency).

```sh
xelatex -jobname='Nick Dobner CV' cv.tex
```
