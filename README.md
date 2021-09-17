# README

This GitHub project is mainly intended for trainees. All the information
is in German.

License: [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)

## Installation

Unter openSUSE, installiere folgende Pakete:

```bash
zypper install --no-recommends texlive-latex texlive-hyperref \
texlive-lineno texlive-xcolor texlive-psnfss texlive-zapfding \
texlive-zapfding-fonts texlive-german texlive-babel-german \
texlive-koma-script
```

## Kompilierung

Um das PDF zu erzeugen, führe aus:

```bash
pdflatex projektarbeit.tex
pdflatex projektarbeit.tex
```

Du musst `pdflatex` zweimal ausführen, um alle Referenzen aufzulösen.

