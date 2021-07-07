Code structure
==============

This page serves to briefly describe the directory structure for ``matching``.
Below is the top-level directory tree (with a few couple of extra directories
removed):

    matching
    ├── docs
    ├── src
    ├── tests
    ├── CHANGES.rst
    ├── CITATION.rst
    ├── CONTRIBUTING.rst
    ├── INSTALLATION.rst
    ├── LICENSE
    ├── README.rst
    ├── paper.bib
    ├── paper.md
    ├── requirements.txt
    └── setup.py


``docs``
--------

The ``docs`` directory contains the code used to create the documentation for
``matching``. Its structure is:

    docs
    ├── data
    ├── discussion
    ├── how-to
    ├── reference
    ├── tex
    ├── tutorials
    ├── bibliography.bib
    ├── environment.yml
    ├── index.rst
    └── requirements.txt


``src``
-------

The ``src`` directory contains the source code for ``matching``. Its structure
is:

    src
    └── matching
        ├── __init__.py
        ├── algorithms
        ├── base.py
        ├── exceptions.py
        ├── games
        ├── matchings.py
        ├── players
        └── version.py


``tests``
---------

The ``tests`` directory contains all of the tests for the ``matching`` source
code. Its structure is:

    tests
    ├── base
    ├── hospital_resident
    ├── players
    ├── stable_marriage
    ├── stable_roommates
    ├── student_allocation
    ├── test_algorithms_util.py
    └── test_matchings.py


