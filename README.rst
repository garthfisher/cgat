.. image:: https://travis-ci.org/CGATOxford/cgat.svg?branch=master
    :target: https://travis-ci.org/CGATOxford/cgat

.. image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat-square
    :target: http://bioconda.github.io/recipes/cgat-scripts/README.html

===========================
The CGAT code collection
===========================

The CGAT code collection has grown out of the work in comparative
genomics by the Ponting group in the last decade. Now, CGAT_ has added
functionality to do next-generation sequencing analysis.

The CGAT Code collection has two components. The first component
is a collection of scripts, the CGAT tools. The second component
is a collection of pipelines. While both components are part of this
collection, we are currently concentrating on publishing the CGAT
tools.

For questions, please open a discussion on the GitHub
`issue page
<https://github.com/CGATOxford/cgat/issues>`_.

Documentation of CGAT tools is available
`here <https://www.cgat.org/downloads/public/cgat/documentation>`_.

CGAT Tools
==========

The CGAT tools can be installed from pypi::

   pip install cgat

More advanced installation options are explained
`here
<https://www.cgat.org/downloads/public/cgat/documentation/CGATInstallation.html>_`.

To use CGAT Tools, use the ``cgat --help`` command. For example, to
strip sequence and quality information from a bam_ file, type:

   cgat bam2bam --strip=sequence < in.bam > out.bam

.. _bam: http://en.wikipedia.org/wiki/SAMtools
.. _CGAT: http://www.cgat.org

