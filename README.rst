EMStudio — User Documentation
=============================

User manual for **EMStudio**, the standalone editor of the Extended Matrix (EM)
language, part of the `Extended Matrix Framework
<https://www.extendedmatrix.org/discover/emf>`_.

The manual follows the `Diátaxis <https://diataxis.fr>`_ system — the same
structure used by the *3D Survey Collection* and *EM-blender-tools* manuals:

- **Tutorial** — learning-oriented, a guided first contact;
- **How-to** — task-oriented recipes grouped by goal;
- **Reference** — information-oriented, tab-by-tab and window-by-window;
- **Explanation** — understanding-oriented, the concepts and the design.

Built with `Sphinx <https://www.sphinx-doc.org>`_ and the Read the Docs theme.

Build locally
-------------

.. code-block:: bash

   python3 -m venv .venv
   .venv/bin/pip install sphinx sphinx_rtd_theme
   .venv/bin/sphinx-build -b html docs docs/_build/html
   # open docs/_build/html/index.html

Screenshots live under ``docs/_static/`` (one folder per page,
``NN_description.png``) and are referenced with ``.. image::`` /
``.. figure::`` using ``:width:`` and a descriptive ``:alt:``.

Authored by Emanuel Demetrescu, CNR-ISPC.
