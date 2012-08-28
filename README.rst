.. Copyright © 2012 Martin Ueding <dev@martin-ueding.de>

############
vim-headings
############

Say you are editing a reStructuredText document and have this::

    page title

Then you can press ``,h1`` (or whatever leader key you have) and it will make
it::

    ##########
    page title
    ##########

If you are editing a LaTeX document, you can use this for sections::

    section

Will become with ``,h1``::

    \section{section}

installation
============

If you use pathogen, then just clone this into your ``.vim/bundle`` directory.
