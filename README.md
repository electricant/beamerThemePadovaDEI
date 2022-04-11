# beamerThemePadovaDEI
Beamer theme for the Department of Information Engineering at the University
of Padova.

## Installation

The theme can be used directly by copying the `*.sty` files in your presentation directory.

Alternatively the theme can be installed locally by adding it to your LaTeX
distribution using the following commands:

    $ mkdir -p ~/texmf/tex/latex/PadovaDEI/

Copy the files in this repo in the newly created folders and recreate the package index with:

    $ texhash ~/texmf
    texhash: Updating /home/user/texmf/ls-R...
    texhash: Done.

### AUR package

For Arch Linux users there is an AUR package:
[aur.archlinux.org/packages/latex-padova-dei][1]

[1]: https://aur.archlinux.org/packages/latex-padova-dei/

## Usage

Declare the teme at the top of your `.tex` file with the line
`\usetheme{PadovaDEI}`.

## License

2020/04/21  
Package version 1.0

(c) 2017 Paolo Scaramuzza \<<paoscr@gmail.com>>
Contributors: Davide Peressoni\<<davide.peressoni@tuta.io>>

This work may be distributed and/or modified under the
conditions of the LaTeX Project Public License, either version 1.3
of this license or (at your option) any later version.
The latest version of this license is in
<http://www.latex-project.org/lppl.txt>
and version 1.3 or later is part of all distributions of LaTeX
version 2005/12/01 or later.

