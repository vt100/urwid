.. image:: https://travis-ci.org/urwid/urwid.png?branch=master
   :alt: build status
   :target: https://travis-ci.org/urwid/urwid/

.. image:: https://coveralls.io/repos/github/urwid/urwid/badge.svg
   :alt: build coverage
   :target: https://coveralls.io/github/urwid/urwid

`Development version documentation <http://urwid.readthedocs.org/en/latest/>`_

**Urwid is looking for new maintainers, please open an issue here to volunteer!**

.. content-start

About
=====

Urwid is a console user interface library for Python.
It includes many features useful for text console application developers including:

- Applications resize quickly and smoothly
- Automatic, programmable text alignment and wrapping
- Simple markup for setting text attributes within blocks of text
- Powerful list box with programmable content for scrolling all widget types
- Your choice of event loops: Twisted, Glib, Tornado or select-based loop
- Pre-built widgets include edit boxes, buttons, check boxes and radio buttons
- Display modules include raw, curses, and experimental LCD and web displays
- Support for UTF-8, simple 8-bit and CJK encodings
- 256 and 88 color mode support
- Compatible with Python 2.6, 2.7, 3.2+ and PyPy

Home Page:
  http://urwid.org/

Testing
=======

To run tests locally, install & run `tox`. You must have
appropriate Python versions installed to run `tox` for
each of them.

To test code in all Python versions:

.. code:: bash

    tox                    # Test all versions specified in tox.ini:
    tox -e py36            # Test Python 3.6 only
    tox -e py27,py36,pypy  # Test Python 2.7, Python 3.6 & pypy
