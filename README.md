pyregion
========

pyregion is a python module to parse ds9 region files.
It also supports ciao region files.

Homepage : http://pyregion.readthedocs.org/

PyPI: http://pypi.python.org/pypi/pyregion

Installation: ``pip install pyregion``

FEATURES
--------

* ds9 and ciao region files.
* (physical, wcs) coordinate conversion to the image coordinate.
* convert regions to matplotlib patches.
* convert regions to spatial filter (i.e., generate mask images)

LICENSE
-------

All files (see exception below) are under MIT License. See LICENSE.

* "lib/kapteyn_celestial.py" is from the Kapteyn package
  (http://www.astro.rug.nl/software/kapteyn/). See
  LICENSE_kapteyn.txt.

Status
------

[![Build Status](https://travis-ci.org/astropy/pyregion.png?branch=master)](https://travis-ci.org/astropy/pyregion)

[![Coverage Status](https://coveralls.io/repos/astropy/pyregion/badge.png?branch=master)](https://coveralls.io/r/astropy/pyregion?branch=master)
