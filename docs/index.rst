.. PSOPy documentation master file, created by
   sphinx-quickstart on Thu Mar 29 00:29:17 2018.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

===============================================================================
The PSOPy Docs
===============================================================================

PSOPy (pronounced "Soapy") is a SciPy compatible super fast Python
implementation for Particle Swarm Optimization. The codes are tested for
standard optimization test functions (both constrained and unconstrained).

The library provides two implementations, one that mimics the interface to
``scipy.optimize.minimize`` and one that directly runs PSO. The SciPy
compatible function is a wrapper over the direct implementation, and therefore
may be slower in execution time, as the constraint and fitness functions are
wrapped.

-------------------------------------------------------------------------------
Contents
-------------------------------------------------------------------------------

.. toctree::
   :maxdepth: 2

   readme/installation
   readme/examples
   apidocs
   readme/references

-------------------------------------------------------------------------------
Authors
-------------------------------------------------------------------------------

- Abhijit Theophilus (abhijit.theo@gmail.com)
- Dr\. Snehanshu Saha (snehanshusaha@pes.edu)
- Suryoday Basak (suryodaybasak@gmail.com)

-------------------------------------------------------------------------------
License
-------------------------------------------------------------------------------

| Licensed under the BSD 3-Clause License.
| Copyright 2018 Abhijit Theophilus, Snehanshu Saha, Suryoday Basak

..
    Indices
    =======

    * :ref:`genindex`
    * :ref:`modindex`
    * :ref:`search`
