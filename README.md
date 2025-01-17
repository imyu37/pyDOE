``pyDOE``: The experimental design package for python
=====================================================

The ``pyDOE`` package is designed to help the 
**scientist, engineer, statistician,** etc., to construct appropriate 
**experimental designs**.

Capabilities
============

The package currently includes functions for creating designs for any 
number of factors:

- *Factorial Designs*

  #. **General Full-Factorial** (``fullfact``)

  #. **2-level Full-Factorial** (``ff2n``)

  #. **2-level Fractional Factorial** (``fracfact``)

  #. **Plackett-Burman** (``pbdesign``)

- *Response-Surface Designs* 

  #. **Box-Behnken** (``bbdesign``)

  #. **Central-Composite** (``ccdesign``)

- *Randomized Designs*

  #. **Latin-Hypercube** (``lhs``)
  
*See the* `package homepage`_ *for details on usage and other notes*

What's New
==========

In this release, an incorrect indexing variable in the internal LHS function
``_pdist`` has been corrected so point-distances are now calculated accurately.

Requirements
============

- NumPy
- SciPy

Installation and download
=========================

See the `package homepage`_ for helpful hints relating to downloading
and installing pyDOE.

Source Code
===========

The latest, bleeding-edge but working `code
<https://github.com/tisimst/pyDOE/tree/master/pyDOE>`_
and `documentation source
<https://github.com/tisimst/pyDOE/tree/master/doc/>`_ are
available `on GitHub <https://github.com/tisimst/pyDOE/>`_.

Contact
=======

Any feedback, questions, bug reports, or success stores should
be sent to the `author`_. I'd love to hear from you!

Credits
=======

This code was originally published by the following individuals for use with
Scilab:
    
- Copyright (C) 2012 - 2013 - Michael Baudin
- Copyright (C) 2012 - Maria Christopoulou
- Copyright (C) 2010 - 2011 - INRIA - Michael Baudin
- Copyright (C) 2009 - Yann Collette
- Copyright (C) 2009 - CEA - Jean-Marc Martinez

- Website: forge.scilab.org/index.php/p/scidoe/sourcetree/master/macros

Much thanks goes to these individuals.

And thanks goes out to the following for finding and offering solutions for
bugs:

- Ashmeet Singh

License
=======

This package is provided under two licenses:

1. The *BSD License* (3-clause)
2. Any other that the author approves (just ask!)

References
==========

- `Factorial designs`_
- `Plackett-Burman designs`_
- `Box-Behnken designs`_
- `Central composite designs`_
- `Latin-Hypercube designs`_

.. _author: mailto:tisimst@gmail.com
.. _Factorial designs: http://en.wikipedia.org/wiki/Factorial_experiment
.. _Box-Behnken designs: http://en.wikipedia.org/wiki/Box-Behnken_design
.. _Central composite designs: http://en.wikipedia.org/wiki/Central_composite_design
.. _Plackett-Burman designs: http://en.wikipedia.org/wiki/Plackett-Burman_design
.. _Latin-Hypercube designs: http://en.wikipedia.org/wiki/Latin_hypercube_sampling
.. _package homepage: http://pythonhosted.org/pyDOE
.. _lhs documentation: http://pythonhosted.org/pyDOE/randomized.html#latin-hypercube
