python-template
=======================

A GitHub repository template for Python projects, which includes configuration for various tools, including:

- `Black`_
- `Flake8`_
- `isort`_
- `Hound`_

This template assumes you will use `Poetry`_ for managing your dependencies, so includes configuration in `pyproject.toml` for Poetry and `poetry.toml` that configures virtualenvs to be created in the project directory. 

isort and flake8 are configured to be compatible with Black formatting standards.

The ``.gitignore`` is configured for Python, based on the ``.gitignore`` `template on GitHub <https://raw.githubusercontent.com/github/gitignore/main/Python.gitignore>`__, plus additional rules ignoring VS Code and IntelliJ IDEA project-specific configuration directories.

An MIT License template can be found in ``LICENSE``, which is **not the license** for this template.

Things for you to do
--------------------

- Edit **this document**, so it describes your project, and not this template.

License
-------

This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or
distribute this software, either in source code form or as a compiled
binary, for any purpose, commercial or non-commercial, and by any
means.

In jurisdictions that recognize copyright laws, the author or authors
of this software dedicate any and all copyright interest in the
software to the public domain. We make this dedication for the benefit
of the public at large and to the detriment of our heirs and
successors. We intend this dedication to be an overt act of
relinquishment in perpetuity of all present and future rights to this
software under copyright law.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR
OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.

For more information, please refer to <http://unlicense.org/>

.. _Black: https://black.readthedocs.io/en/stable/
.. _Flake8: https://flake8.pycqa.org
.. _isort: https://pycqa.github.io/isort/
.. _Hound: https://www.houndci.com
.. _Python: https://python-poetry.org/
