
Introduction
============

This demo is:

* Proof of concept for mr.migrator: A tool that provides the ability to
  register and execute collective.transmogrifier pipelines without creating a
  Python package. It's Miller Time™.

Installation
============

You can try out this demo::

    $ git clone git@github.com:aclark4life/mr_migrator_demo.git
    $ cd mr_migrator_demo
    $ python bootstrap.py
    $ bin/buildout
    $ bin/plone start
    $ bin/migrate

You should end up with content in Plone that looks like this:

.. image:: https://github.com/aclark4life/mr_migrator_demo/raw/master/content.png
