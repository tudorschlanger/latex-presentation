# LaTeX template for academic presentations

This repository contains a minimalistic template to write academic presentations with LaTeX Beamer.

## Included files and how to use them

- `presentation.tex` –  Skeleton of the presentation. Fill it out with the content of your presentation.
- `presentation.sty` –  LaTeX style file collecting all the formatting commands. Must be included in the same folder as `presentation.tex`.
- `math.sty` – LaTeX style file collecting many mathematical commands. Must be included in the same folder as `presentation.tex`. This file is hosted and described [in this GitHub repository](https://github.com/pmichaillat/latex-math). 
- `figures.pdf` – PDF file with all the figures included in the presentation. Replace the figures with your own figures---one per page. An easy way to do that is to create a Keynote or Powerpoint presentation; insert each figure as a slide background; and save the resulting presentation as PDF. With this method, all the figures have the exact same size. It is also possible to use Keynote or Powerpoint to annotate easily the figures created with an external software (Matlab, R, and so on).
- `presentation.pdf` – PDF file produced by compiling `presentation.tex` (with PDFTeX). This file is not required to use the template; it only illustrate the output of the template.

## Key features

- The font for text, roman math, and numbers is [Source Sans Pro](https://fonts.google.com/specimen/Source+Sans+Pro).
- The font for Greek and calligraphic math is [Euler](http://luc.devroye.org/fonts-26139.html).
- No colors are used in the text (only black/gray) to reduce distraction.
- Colors are reserved for graphs and alerts.
- Margins, spacing, and font size are set for comfortable reading.

## Reference

As much as possible the template follows Matthew Butterick's wonderful typographical advice in [Practical Typography](https://practicaltypography.com)—especially the [section on presentations](https://practicaltypography.com/presentations.html).
