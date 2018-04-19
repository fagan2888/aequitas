==========
Aequitas
==========

----------------------------------------------
Bias and Fairness Audit Library for Machine Learning Systems
----------------------------------------------

An open-source bias audit toolkit for machine learning developers, analysts, and policymakers to audit machine learning models for discrimination and bias, and to make informed and equitable decisions around developing and deploying predictive risk-assessment tools.

Learn more about the project at http://dsapp.uchicago.edu/aequitas/

Demo
====

See what Aequitas can do at http://aequitas.dssg.io/.

Sample Jupyter Notebook
====

Explore bias analysis of the COMPAS data using the Aequitas library (https://github.com/dssg/aequitas/blob/master/docs/source/examples/compas_demo.ipynb)

Documentation
===

Find documentation at https://dssg.github.io/aequitas/

Installation
============

Aequitas requires Python 3.

Install this Python library from source::

    python setup.py install

...or named as an installation requirement, *e.g.* via ``pip``::

    pip install git+https://github.com/dssg/aequitas.git

You may then import the ``aequitas`` module from Python::

    import aequitas

...or execute the auditor from the command line::

    aequitas-report

Development
===========

Provision your development environment via ``install``::

    ./install

Common development tasks, such as deploying the webapp, may then be handled via ``manage``::

    manage --help

Find documentation at https://dssg.github.io/aequitas/
