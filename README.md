# UiS-beamer

Unofficial University of Stavanger / Universitetet i Stavanger (UiS) (https://www.uis.no/) Beamer presentation template by Nithiya Streethran (nmstreethran@gmail.com). This was replicated based on the official PowerPoint template. 

I made this template for my own use. Please feel free to suggest improvements (see the [contributing guidelines](/CONTRIBUTING.md)). This is a work-in-progress.

## Description of files

* Main file: [presentation.tex](/presentation.tex)
* PDF output: [presentation.pdf](/presentation.pdf)
* Images: [images/](/images/) 
* Style file: [uisbeamer.sty](/uisbeamer.sty)
* Main content slides: [body.tex](/body.tex)
* References and appendices / backup slides: [backup.tex](/backup.tex)
* Code of conduct: [CODE_OF_CONDUCT.md](/CODE_OF_CONDUCT.md)
* Bibliography: [sample.bib](/sample.bib)
* Contributing guidelines: [CONTRIBUTING.md](/CONTRIBUTING.md)
* License: [LICENSE](/LICENSE)

## Sources

This template uses the [`beamer`](https://ctan.org/pkg/beamer) class. Some of the examples are taken from [Overleaf](https://www.overleaf.com/). The bibliography sample [sample.bib](/sample.bib) was taken from [this link](http://ctan.cs.uu.nl/macros/latex/contrib/biblatex/doc/examples/biblatex-examples.bib). The logos, background image and colours are from [Universitetet i Stavanger profilmanual](http://uis.profilmanual.fasett.no/universitetet-i-stavanger-profilmanual-1). The contributing guideline was adapted from the [Open Science MOOC](https://github.com/OpenScienceMOOC/Module-5-Open-Research-Software-and-Open-Source/blob/master/CONTRIBUTING.md).

## Compilation

PdfLaTeX > Biber > PdfLaTeX > PdfLaTeX

Compiled using [latexmk](https://ctan.org/pkg/latexmk) on [VSCodium](https://vscodium.github.io/) (open-source alternative to [Visual Studio Code](https://code.visualstudio.com/)) with [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) and [texlive](https://tug.org/texlive/).

## License

[uisbeamer.sty](/uisbeamer.sty): [![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)