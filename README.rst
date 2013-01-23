.. Copyright © 2012-2013 Martin Ueding <dev@martin-ueding.de>

############
vim-headings
############

:License (Code): CC0_
:License (Text): CC-BY_
:Tags: Vim

Say you are editing a reStructuredText document and have this::

    page title

Then you can press ``<leader>h1`` and it will make it::

    ##########
    page title
    ##########

If you are editing a LaTeX document, you can use this for sections::

    section

Will become with ``<leader>h1``::

    \section{section}

For LaTeX, there are versions with a capital letter that will produce an ASCII
box. This only works, if ``<leader>bl`` creates the box. Use this (with the
``boxes`` command installed)::

    vnoremap <leader>bl !boxes -a c -s 79 -d latex<CR>

installation
============

If you use pathogen, then just clone this into your ``.vim/bundle`` directory.

.. _CC-BY: https://creativecommons.org/licenses/by/3.0/
.. _CC0: https://creativecommons.org/publicdomain/zero/1.0/
