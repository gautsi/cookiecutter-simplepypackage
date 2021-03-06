======================
cookiecutter-simplepypackage
======================

Simple cookiecutter template for a Python package. Based on https://github.com/audreyr/cookiecutter-pypackage.

* Free software: BSD license
* Testing with `unittest`, `python setup.py test` and `pytest` for doctesting
* Travis-CI_: Ready for Travis Continuous Integration testing
* Tox_ testing: Setup to easily test for Python 2.7 and 3.4
* Sphinx_ docs: Documentation ready for generation with, for example, ReadTheDocs_

Usage
-----

Generate a Python package project::

    cookiecutter https://github.com/gautsi/cookiecutter-simplepypackage.git

Then:

* Create a repo and put it there.
* Add the repo to your Travis CI account.
* Add the repo to your ReadTheDocs account + turn on the ReadTheDocs service hook.
