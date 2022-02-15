========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |github-actions| |requires|
        | |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/rainbowprint/badge/?style=flat
    :target: https://rainbowprint.readthedocs.io/
    :alt: Documentation Status

.. |github-actions| image:: https://github.com/Techno-Hwizrdry/rainbowprint/actions/workflows/github-actions.yml/badge.svg
    :alt: GitHub Actions Build Status
    :target: https://github.com/Techno-Hwizrdry/rainbowprint/actions

.. |requires| image:: https://requires.io/github/Techno-Hwizrdry/rainbowprint/requirements.svg?branch=main
    :alt: Requirements Status
    :target: https://requires.io/github/Techno-Hwizrdry/rainbowprint/requirements/?branch=main

.. |codecov| image:: https://codecov.io/gh/Techno-Hwizrdry/rainbowprint/branch/main/graphs/badge.svg?branch=main
    :alt: Coverage Status
    :target: https://codecov.io/github/Techno-Hwizrdry/rainbowprint

.. |version| image:: https://img.shields.io/pypi/v/rainbowprint.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/rainbowprint

.. |wheel| image:: https://img.shields.io/pypi/wheel/rainbowprint.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/rainbowprint

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/rainbowprint.svg
    :alt: Supported versions
    :target: https://pypi.org/project/rainbowprint

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/rainbowprint.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/rainbowprint

.. |commits-since| image:: https://img.shields.io/github/commits-since/Techno-Hwizrdry/rainbowprint/v0.0.1.svg
    :alt: Commits since latest release
    :target: https://github.com/Techno-Hwizrdry/rainbowprint/compare/v0.0.1...main



.. end-badges

Prin in colorful gradients.

* Free software: MIT license

Installation
============

::

    pip install rainbowprint

You can also install the in-development version with::

    pip install https://github.com/Techno-Hwizrdry/rainbowprint/archive/main.zip


Documentation
=============


https://rainbowprint.readthedocs.io/


Development
===========

To run all the tests run::

    tox

Note, to combine the coverage data from all the tox environments run:

.. list-table::
    :widths: 10 90
    :stub-columns: 1

    - - Windows
      - ::

            set PYTEST_ADDOPTS=--cov-append
            tox

    - - Other
      - ::

            PYTEST_ADDOPTS=--cov-append tox
