# TCC em LaTeX com ABNT

![The Librarian](https://upload.wikimedia.org/wikipedia/commons/thumb/7/70/Bibliotekarien_konserverad_-_Skoklosters_slott_-_97136.tif/lossy-page1-700px-Bibliotekarien_konserverad_-_Skoklosters_slott_-_97136.tif.jpg)

*"The Librarian" (1566) by Giuseppe Arcimboldo — [Wikipedia](https://en.wikipedia.org/wiki/The_Librarian_(Arcimboldo))*

A LaTeX template for Brazilian undergraduate theses (TCC) following ABNT formatting standards.

## About

In Brazil, most undergraduate programs require a final capstone project called a *Trabalho de Conclusao de Curso* (TCC), formatted according to ABNT (Associacao Brasileira de Normas Tecnicas) standards. This repository provides the LaTeX source I used for my own TCC, made available so others can use it as a starting point.

I completed my TCC as a dual-degree requirement for both **Law** (FGV DIREITO RIO) and **Applied Mathematics** (EMAp/FGV). Since I was in a joint program, a single thesis satisfied both degrees.

Using LaTeX with the [abnTeX2](https://www.abntex.net.br/) package saved a significant amount of time on formatting, letting me focus on content instead of wrestling with margins and citation styles.

> **Note**: The thesis content is in Portuguese. This README is in English for portfolio visibility.

## Overleaf Source

The full LaTeX source is available as a read-only Overleaf project:

**[View on Overleaf](https://www.overleaf.com/read/frsdddmzbhnr)**

## Final PDF

The final version of the thesis is archived in the FGV digital library:

- [PDF (full text)](http://bibliotecadigital.fgv.br/dspace/bitstream/handle/10438/24728/PEDRO%20DELFINO.pdf?sequence=1&isAllowed=y)
- [Library metadata](http://bibliotecadigital.fgv.br/dspace/handle/10438/24728)

## Tech Stack

- **Typesetting**: LaTeX
- **ABNT compliance**: [abnTeX2](https://www.abntex.net.br/) package
- **Editor**: Overleaf (cloud) / Emacs (local)

## Notes

- The default abnTeX2 citation style is numeric (e.g., `[2]`). I switched to author-date format (e.g., `(DELFINO, 2018)`) since it is more conventional in legal academia. This change is straightforward to toggle.
- Hat tip to the abnTeX2 maintainers -- especially [@laurocesar](https://github.com/laurocesar) -- for building a great tool. The name "abnTeX" (*Absurdas Normas para TeX*) is a well-deserved pun.

## Author

Pedro Delfino -- [GitHub](https://github.com/pdelfino) -- [pedrodelfino.com](https://pedrodelfino.com)
