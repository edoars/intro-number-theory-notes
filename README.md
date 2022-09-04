# Introduction to Number Theory notes

Notes (in italian) for the undergraduate Introduction to Number Theory course (TN410 - Introduzione alla teoria dei numeri) at University of Roma Tre, academic year 2015/2016.

The pdf file is available in the Releases.

## Manual build

The notes are compiled via latexmk with the custom class `edoars-notes.cls` found in this repository as a submodule. You will need to have an up-to-date distribution of LaTeX and the Latexmk utility.

First clone the repository and submodules:

``` sh
git clone --recurse-submodules https://github.com/edoars/intro-number-theory-notes
```

Then build the notes with `make`:

``` sh
make all
```

The latex document will be compiled into `main.pdf`.
