TODO
====

## latex-base

* Do not skip template rendering for `Makefile` and `make/*`. Need to make sure
  there is no interference with latex code.

* Track dependencies of `.aux` and `.toc` files.

  Extend preamble script to handle journal styles.

* Fix troubles with bibliography

* Make loud error messages when tex dependencies do not exist. I should proably
  instantiate rules explicitly instead of relying on complex pattern rules.

* move gitref stuff from `draftools.lua` to the Makefile. Want to general gitref.tex with
  the corresponding tex code for the header.

* Find a good way to store the template source within the project.

## latex-slides

* brackets do not stretch. In particular a cases environment is ugly. either
  make them stretch, or use a proper math font for the brackets.

