========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |appveyor| |requires|
        | |codecov|
    * - package
      - |version| |downloads| |wheel| |supported-versions| |supported-implementations|

.. |docs| image:: https://readthedocs.org/projects/python-nameless/badge/?style=flat
    :target: https://readthedocs.org/projects/python-nameless
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/constanthatz/python-nameless.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/constanthatz/python-nameless

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/constanthatz/python-nameless?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/constanthatz/python-nameless

.. |requires| image:: https://requires.io/github/constanthatz/python-nameless/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/constanthatz/python-nameless/requirements/?branch=master

.. |codecov| image:: https://codecov.io/github/constanthatz/python-nameless/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/constanthatz/python-nameless

.. |version| image:: https://img.shields.io/pypi/v/nameless.svg?style=flat
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/nameless

.. |downloads| image:: https://img.shields.io/pypi/dm/nameless.svg?style=flat
    :alt: PyPI Package monthly downloads
    :target: https://pypi.python.org/pypi/nameless

.. |wheel| image:: https://img.shields.io/pypi/wheel/nameless.svg?style=flat
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/nameless

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/nameless.svg?style=flat
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/nameless

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/nameless.svg?style=flat
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/nameless


.. end-badges

An example package. Generated with cookiecutter-pylibrary.

* Free software: BSD license

Installation
============

::

    pip install nameless

Documentation
=============

https://python-nameless.readthedocs.io/

Development
===========

To run the all tests run::

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
