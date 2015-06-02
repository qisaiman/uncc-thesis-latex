uncc-thesis-latex
=================

LaTeX template for UNC-Charlotte dissertations.

No need to use the makefile if you're using a GUI editor, but if you're on the command line (e.g. vim, emacs), you can compile your dissertation with `make`.

additional changes
-------------------

* use biblatex for citation managements
* use lualatex for truetype font (such as Times New Roman)
* For a full compiling run: 
    * Lualatex dissertation.tex
    * Biber dissertation.tex
    * Make Acronyms dissertation.tex
    * Lualatex dissertation.tex
    * Lualatex dissertation.tex

Note: Window OS, TeXworks 2013 or later assumed.