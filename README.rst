.. Copyright © 2012-2014, 2016-2017 Martin Ueding <dev@martin-ueding.de>

##################
pdflatex-multifont
##################

If you want to try different fonts (with math support) for a given document,
you can use this script to render it in different fonts.

Call it like so::

    pdflatex-multifonts document.tex

And it will generate a whole bunch of documents like ``document-{lmodern}.pdf``
or ``document-[charter]{mathdesign}.pdf``.

Needs ``pdflatex`` and ``latexmk``.
