.. image:: https://travis-ci.org/nose-devs/nose2.svg?branch=master
    :target: https://travis-ci.org/nose-devs/nose2
    :alt: Build Status

.. image:: https://coveralls.io/repos/github/nose-devs/nose2/badge.svg?branch=master
    :target: https://coveralls.io/github/nose-devs/nose2?branch=master
    :alt: Coverage Status

.. image:: https://img.shields.io/pypi/v/nose2.svg
    :target: https://pypi.org/project/nose2/
    :alt: Latest PyPI version

.. image:: https://badges.gitter.im/gitterHQ/gitter.svg
    :target: https://gitter.im/nose2
    :alt: Gitter Channel

Welcome to nose2
================

``nose2`` is the successor to ``nose``.

It's ``unittest`` with plugins.

``nose2`` is a new project and does not support all of the features of
``nose``. See `differences`_ for a thorough rundown.

nose2's purpose is to extend ``unittest`` to make testing nicer and easier to
understand.

nose2 vs pytest
---------------

``nose2`` may or may not be a good fit for your project.

If you are new to python testing, we encourage you to also consider `pytest`_,
a popular testing framework.

Full Docs
---------

Full documentation for ``nose`` is available on `readthedocs`_.

Contributing
------------

If you want to make contributions, you can use the ``Makefile`` to get started
quickly and easily::

    # All you need is a supported version of python and virtualenv installed
    make test

Don't worry if you don't have all supported versions installed.
Your changes will get tested automatically when you make a PR.

Use ``make help`` to see other options, and read the `contributing`_ guide for
full detail.

.. _differences: https://nose2.readthedocs.io/en/latest/differences.html

.. _pytest: http://pytest.readthedocs.io/en/latest/

.. _contributing: https://github.com/nose-devs/nose2/blob/master/contributing.rst

.. _readthedocs: https://nose2.readthedocs.io/en/latest/
