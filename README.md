# uni-stuttgart-beamer-template

This is an unofficial L<sup>A</sup>T<sub>E</sub>X template for Beamer
presentations by and for members of the University of Stuttgart,
Germany, following the new corporate design the university has given
itself in 2016.

The template is private work by members of the University of Stuttgart.
It is not endorsed by the University of Stuttgart or any of its
institutions, institutes, or departments.
The template is made available to the public as we think it might
be useful for other people.
Neither the authors nor the University of Stuttgart provide support
for the template going beyond this `README`.

The license for the template is located in `LICENSE`.

If you happen to improve the template, it would be nice if you merged
back your work using pull requests.

## Usage

The directory `tex` contains L<sup>A</sup>T<sub>E</sub>X source code
and resulting PDFs, while `gfx` contains graphics.
The main component of the template is the new Beamer theme "Stuttgart",
located in `tex/beamerthemeStuttgart.sty`.
Also included is an example presentation in `tex/talk.pdf`
(L<sup>A</sup>T<sub>E</sub>X source in
`tex/talk.tex` and `tex/slides.tex`).

## Building

On Ubuntu/Debian install package texlive-full. This package includes latexmk.
To build the presentation, simply run the supplied Makefile.


### PDFL<sup>A</sup>T<sub>E</sub>X

Of course, you can also compile the example presentation in the
traditional way using
```
cd tex
pdflatex talk.tex
```
