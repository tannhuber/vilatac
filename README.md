# ViLaTaC (Vim LaTeX Table Creator)

easy table creator for LaTeX, created for vim with the vim-latex plugin

# Why?

LaTeX is nice. Creating tables is horrible. The [perl-latex-table][1] script
does not support all the features that I use frequently, e.g. multicolumns,
cmidrules, and so on. With ViLaTac it is really easy to create tables for print and
publishing.

# Features

* supports multicolumns, cmidrules, left/right alignment, captions, labels
* table header and body fonts can be defined in script file
* vim-latex jump marks

# Installation

* set fonts in vilatac
* copy vilatac somewhere to your $PATH, e.g. ~/bin/
* put key mapping into ~/.vimrc: cmap TAB !vilatac<CR><C-j>

# Usage
See sample.tex.

# Alternatives
[1]: https://aur.archlinux.org/packages/perl-latex-table/
