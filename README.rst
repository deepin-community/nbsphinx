Jupyter Notebook Tools for Sphinx
=================================

``nbsphinx`` is a Sphinx_ extension that provides a source parser for
``*.ipynb`` files.
Custom Sphinx directives are used to show `Jupyter Notebook`_ code cells (and of
course their results) in both HTML and LaTeX output.
Un-evaluated notebooks -- i.e. notebooks without stored output cells -- will be
automatically executed during the Sphinx build process.

Quick Start:
    #. Install ``nbsphinx``

    #. Edit your ``conf.py`` and add ``'nbsphinx'`` to ``extensions``.

    #. Edit your ``index.rst`` and add the names of your ``*.ipynb`` files
       to the ``toctree``.

    #. Run Sphinx!

Online documentation (and example of use):
    https://nbsphinx.readthedocs.io/

Source code repository (and issue tracker):
    https://github.com/spatialaudio/nbsphinx/

License:
    MIT -- see the file ``LICENSE`` for details.

.. _Sphinx: https://www.sphinx-doc.org/
.. _Jupyter Notebook: https://jupyter.org/
