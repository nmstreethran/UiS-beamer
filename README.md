# uis-beamer

Unofficial [University of Stavanger (UiS)](https://www.uis.no/) Beamer presentation template by Nithiya Streethran (nmstreethran@gmail.com). This was created based on the official PowerPoint template, the [Beamer user guide](https://ctan.org/pkg/beamer) and the [Beamer template tutorial by Claudio Fiandrino](https://tex.stackexchange.com/a/146682/140109). Most of the examples used are taken from [Overleaf](https://www.overleaf.com/learn/latex/Beamer).

I made this template for my own use. Please feel free to suggest improvements (see the [contributing guidelines](/CONTRIBUTING.md) and code of conduct: [CODE_OF_CONDUCT.md](/CODE_OF_CONDUCT.md)). 

Known issue(s): 

- PDF encoding error `Token not allowed in a PDF string` 

## Description of files

* Main file: [uis-example.tex](/uis-example.tex)
* PDF output: [uis-example.pdf](/uis-example.pdf) 
* Images: stored in the [images](/images/) folder
* Theme style files: 
  * [beamerthemeuis.sty](/beamerthemeuis.sty)
  * [beamercolorthemeuis.sty](/beamercolorthemeuis.sty)
  * [beamerinnerthemeuis.sty](/beamerinnerthemeuis.sty)
  * [beamerouterthemeuis.sty](/beamerouterthemeuis.sty)
* Bibliography: [sample.bib](/sample.bib)

## Credits

- Bibliography sample [sample.bib](/sample.bib): [CTAN BibLaTeX examples](http://ctan.cs.uu.nl/macros/latex/contrib/biblatex/doc/examples/biblatex-examples.bib)
- Logos, background image and colours: [Universitetet i Stavanger profilmanual](http://uis.profilmanual.fasett.no/universitetet-i-stavanger-profilmanual-1)
- Contributing guideline: adapted from the [Open Science MOOC](https://github.com/OpenScienceMOOC/Module-5-Open-Research-Software-and-Open-Source/blob/master/CONTRIBUTING.md)

## Compilation

PdfLaTeX > Biber > PdfLaTeX > PdfLaTeX

Compiled on [VSCodium](https://vscodium.github.io/) (open-source alternative to [Visual Studio Code](https://code.visualstudio.com/)) with [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) and [TeXlive](https://tug.org/texlive/).

## License

[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
