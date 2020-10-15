# README

This GitHub project is mainly intended for trainees. All the information
is in German.

## Installation

Unter openSUSE, installiere folgende Pakete:

    $ zypper install --no-recommends texlive-latex texlive-hyperref \
       texlive-lineno texlive-xcolor texlive-psnfss \
       texlive-zapfding texlive-zapfding-fonts

# Kompilierung

Um das PDF zu erzeugen, führe aus:

    $ pdflatex projektarbeit.tex
    $ pdflatex projektarbeit.tex

Du musst `pdflatex` zweimal ausführen, um alle Referenzen aufzulösen.
