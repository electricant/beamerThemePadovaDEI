# beamerThemePadovaDEI
Beamer theme for the Department of Information Engineering at the University of Padova.

## Installation

The theme can be used directly by copying the `*.sty` files in your presentation directory.

Alternativelly the theme can be installed localyy by adding it to your LaTeX distibution using the following commands:

    $ mkdir -p ~/texmf/tex/latex/PadovaDEI/

Copy the files in this repo in the newly created folders and recreate the package index with:

    $ texhash ~/texmf
    texhash: Updating /home/user/texmf/ls-R...
    texhash: Done.

### AUR package

For Arch Linux users there is an AUR package: [aur.archlinux.org/packages/latex-padova-dei](https://aur.archlinux.org/packages/latex-padova-dei/)

## Usage

Declare the teme at the top of your `.tex` file with the line `\usetheme{PadovaDEI}`.
