.. image:: https://api.travis-ci.org/dataflake/dataflake.fakeldap.svg?branch=master
   :target: https://travis-ci.org/dataflake/dataflake.fakeldap

.. image:: https://readthedocs.org/projects/dataflakefakeldap/badge/?version=latest
   :target: https://dataflakefakeldap.readthedocs.io
   :alt: Documentation Status

.. image:: https://img.shields.io/pypi/v/dataflake.fakeldap.svg
   :target: https://pypi.python.org/pypi/dataflake.fakeldap
   :alt: PyPI

.. image:: https://img.shields.io/pypi/pyversions/dataflake.fakeldap.svg
   :target: https://pypi.python.org/pypi/dataflake.fakeldap
   :alt: Python versions


====================
 dataflake.fakeldap
====================
This package offers a mock ``pyldap`` library that can be used for testing code relying on ``pyldap`` without having to configure and populate a real directory server.

It's been forked from `dataflake <https://github.com/dataflake/dataflake.fakeldap>`_ for Addepar.


Documentation
=============
Full documentation is available at `readthedocs <https://dataflakefakeldap.readthedocs.io>`_.


Bug tracker
===========
A bug tracker is available `here <https://github.com/dataflake/dataflake.fakeldap/issues>`_.


Package and publish
===================
Requirements:

- A `packagecloud.io <https://packagecloud.io/>`_ key with an environment variable set to it, i.e.: ``PACKAGE_CLOUD_KEY="PACKAGECLOUDKEY"``
- A clean worktree


Run ``./build.sh`` (`build.sh <https://github.com/Addepar/dataflake.fakeldap/blob/addepar/master/build.sh>`_).
