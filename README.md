# ViLaTaC (Vim LaTeX Table Creator)

easy table creator for LaTeX, created for vim with the vim-latex plugin.

# Why?

LaTeX is nice. Creating tables is horrible. The [perl-latex-table][1] script
does not support all the features that I use frequently, e.g. multicolumns,
cmidrules, and so on. With ViLaTaC it is really easy to create tables for print and
publishing.

# Features

* minimalistic syntax
* very flexible
* multicolumns
* cmidrules
* individual column formatting
* different font styles for table header and body can be defined in script file
* vim-latex jump marks for captions and labels

# Installation

* set fonts in vilatac
* copy vilatac somewhere to your $PATH, e.g. ~/bin/
* check, that it is executable (chmod +x ~/bin/vilatac)
* put key mapping into ~/.vimrc: cmap TAB !vilatac<CR><C-j>

# Usage
Learning by doing. Try the examples in sample.tex.

# Other editors
I know, there are other editors. You can use LaTaC with them. The only
difference is that the jump marks were removed.

# Alternatives
* latac (it's in this repository)
* [https://aur.archlinux.org/packages/perl-latex-table/][1]

[1]: https://aur.archlinux.org/packages/perl-latex-table/
