# uis-beamer

Unofficial [University of Stavanger (UiS)](https://www.uis.no/) Beamer presentation template by Nithiya Streethran (nmstreethran at gmail dot com). This was created based on the official PowerPoint template, the [Beamer user guide](https://ctan.org/pkg/beamer) and the [Beamer template tutorial by Claudio Fiandrino](https://tex.stackexchange.com/a/146682/140109).

**I made this template for my own use. Since I am no longer affiliated with UiS, I do not have use for this template. Feel free to use these files to create an improved version.**

Known issue(s):

- PDF encoding error `Token not allowed in a PDF string` - see [josephwright/beamer/issues/449](https://github.com/josephwright/beamer/issues/449)

## Description of files

- Main file: [uis-example.tex](uis-example.tex)
- PDF output: [uis-example.pdf](uis-example.pdf) ([raw / download](https://raw.githubusercontent.com/nmstreethran/uis-beamer/master/uis-example.pdf))
- Images: stored in the [images](images/) folder
- Theme style file: [beamerthemeuis.sty](beamerthemeuis.sty)
- Bibliography: [sample.bib](sample.bib)

## Credits

- examples may be derived from [TeX Stack Exchange](https://tex.stackexchange.com/) (CC BY SA), [Wikibooks](https://en.wikibooks.org/wiki/LaTeX) (CC BY SA), CTAN documentation, and [Overleaf](https://www.overleaf.com/learn)
  - a longtable example by [LianTze Lim on Overleaf](https://www.overleaf.com/latex/examples/a-longtable-example/xxwzfxkxxjmc) (CC BY 4.0)
  - sample bibliography from [CTAN's BibLaTeX examples](http://mirrors.ctan.org/macros/latex/contrib/biblatex/doc/examples/biblatex-examples.bib)
  - listings configuration from [karlkoeller on TeX StackExchange](https://tex.stackexchange.com/a/235822/140109)
- example images are from [Wikimedia Commons](https://commons.wikimedia.org/wiki/Main_Page)
  - Eurasian tree sparrow (*Passer montanus malaccensis*), adult male, in Kuala Lumpur, Malaysia; taken on 31 January 2019, 15:20:47 by [Peter P. Othagoer](https://commons.wikimedia.org/wiki/File:Passer_montanus_malaccensis_@_Kuala_Lumpur,_Malaysia_%281%29.jpg) (CC BY 4.0)
- some examples are my own work
  - Python code samples from [nithiya/ml-elec-model](https://gitlab.com/nithiya/ml-elec-model) (MIT)
- Logos, background image and colours: [Universitetet i Stavanger profilmanual](http://uis.profilmanual.fasett.no/universitetet-i-stavanger-profilmanual-1)
- Contributing guideline: adapted from the [Open Science MOOC](https://github.com/OpenScienceMOOC/Module-5-Open-Research-Software-and-Open-Source/blob/master/CONTRIBUTING.md)

## Packages and compilation

These packages are available on [CTAN](https://www.ctan.org/).

Some packages have additional dependencies not listed here. It is recommended to use a TeX distribution, such as [TeX Live](https://tug.org/texlive/), which comes with all of these packages and their requirements.

Document class: [beamer](https://www.ctan.org/pkg/beamer)

Packages:

- [amsmath](https://www.ctan.org/pkg/amsmath)
- [biblatex](https://www.ctan.org/pkg/biblatex)
- [booktabs](https://www.ctan.org/pkg/booktabs)
- [graphicx](https://www.ctan.org/pkg/graphicx)
- [listings](https://www.ctan.org/pkg/listings)

Fonts, icons, and symbols:

- [newtxtt](https://www.ctan.org/pkg/newtxtt)
- [cabin](https://www.ctan.org/pkg/cabin)
- [fontawesome5](https://www.ctan.org/pkg/fontawesome5)
- [GFSNeohellenicMath](https://www.ctan.org/pkg/gfsneohellenicmath)

Temporary packages:

- [lipsum](https://www.ctan.org/pkg/lipsum) (for generating dummy text)

Compilation: [XeLaTeX](https://www.ctan.org/pkg/xetex) -> [biber](https://www.ctan.org/pkg/biber) -> XeLaTeX -> XeLaTeX

## License

GNU General Public License, Version 3 (GPL-3.0)
