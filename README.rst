
This is forked from - http://pylint.pycqa.org/
============================================

.. image:: https://travis-ci.org/PyCQA/pylint.svg?branch=master
    :target: https://travis-ci.org/PyCQA/pylint

.. image:: https://ci.appveyor.com/api/projects/status/rbvwhakyj1y09atb/branch/master?svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/PCManticore/pylint

.. image:: https://coveralls.io/repos/github/PyCQA/pylint/badge.svg?branch=master
    :target: https://coveralls.io/github/PyCQA/pylint?branch=master


.. image:: https://img.shields.io/pypi/v/pylint.svg
    :alt: Pypi Package version
    :target: https://pypi.python.org/pypi/pylint

.. image:: https://readthedocs.org/projects/pylint/badge/?version=latest
    :target: http://pylint.readthedocs.io/en/latest/?badge=latest
    :alt: Documentation Status

.. image:: https://img.shields.io/badge/code%20style-black-000000.svg
    :target: https://github.com/ambv/black

======
Silent (cylint)
======

**Cython optimized pylint**

Install
-------

Silent can be simply installed by running::

    pip install silent


Testing
-------

We use tox_ for running the test suite. You should be able to install it with::

    pip install tox pytest


To run the test suite for a particular Python version, you can do::

    tox -e py37


For more detailed information, check the documentation.

.. _here: http://pylint.pycqa.org/en/latest/user_guide/installation.html
.. _tox: https://tox.readthedocs.io/en/latest/
