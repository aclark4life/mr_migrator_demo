
Introduction
============

This demo is:

- Proof of concept for mr.migrator: A tool that provides the ability to
  register and execute collective.transmogrifier pipelines without creating a
  Python package. It's Miller Time™.

- Also proof of concept for collective.transmogrifier with the CMFCore
  dependency removed (and a zope.component dependency added in its place).
  It's Scotch time™.

Explanation
-----------

It relies on:

- https://svn.plone.org/svn/collective/collective.transmogrifier/branches/aclark-mr-migrator-compat
- https://svn.plone.org/svn/collective/transmogrify.filesystem/branches/aclark-mr-migrator-compat
- git@github.com:aclark4life/transmogrify.ploneremote.git 

to work. These are, respectively:

- A branch of c.transmogrifier with a setuptools entry point plugin system
  added, and the CMFCore dependencies removed (gracefully, I hope).
- A branch of t.filesystem with the collective.transmogrifier entry point
  specified.
- A fork of t.ploneremote with the collective.transmogrifier entry point
  specified.
