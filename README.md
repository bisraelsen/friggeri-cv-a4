# About

Fork of the ShareLateX version of the [Friggeri CV](https://www.sharelatex.com/templates/cv-or-resume/fancy-cv) from Adrien Friggeri changed to render in A4 paper format. There is also a new option `nocolors` to disable use of colors in section headers. See the samples folder for examples.

# Usage

## Options

* `print`: renders in black and white, and reverts the header to dark on light
* `nocolors`: no colors in section headers (but still use dark header)

In order to compile you need:

* TikZ,
* XeTex,
* fontspec
* biblatex and
* textpos

Keeping the fonts in the root directory makes it so you shouldn't have to install them.

