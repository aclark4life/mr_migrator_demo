
Introduction
============

This repository demonstrates how to use `mr.migrator`_ to import static website content from
the file system into Plone.

Installation
============

Follow these steps::

    $ git clone git@github.com:aclark4life/mr_migrator_demo.git
    $ cd mr_migrator_demo
    $ python2.7 bootstrap.py -d
    $ bin/buildout
    $ bin/plone start
    $ bin/migrate

You should end up with content in Plone that looks like this:

.. image:: https://github.com/aclark4life/mr_migrator_demo/raw/master/screenshot.png

.. _`mr.migrator`: http://pypi.python.org/pypi/mr.migrator
