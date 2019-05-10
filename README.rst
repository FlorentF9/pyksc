PY-KSC
======

**This project is forked from flaviovdf/pyksc and is adapted to run with Python 3.**

Implementation of the KSC time series clustering algorithm.
See [1]_ for details:

Dependencies for library
------------------------
   * Numpy
   * Cython

Dependencies for scripts
------------------------
   * Scipy
   * Matplotlib

How to install
--------------

Clone the repo

::

$ git clone https://github.com/flaviovdf/pyksc.git

Make sure you have cython and numpy. If not run as root (or use your distros package manager)

::

$ pip install numpy

::

$ pip install Cython

Install

::

$ python setup.py install

If you see the following error ``/usr/bin/ld: cannot find -lblas`` on linux, try installing the following two libraries 

::

$ sudo apt-get install libblas-dev liblapack-dev



References
----------
.. [1] J. Yang and J. Leskovec, 
   "Patterns of Temporal Variation in Online Media" - WSDM'11  
   http://dl.acm.org/citation.cfm?id=1935863
