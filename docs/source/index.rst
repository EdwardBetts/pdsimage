.. pdsimage documentation master file, created by
   sphinx-quickstart on Fri Jan  8 16:26:09 2016.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to pdsimage's documentation!
====================================

The Lunar Reconnaissance Orbiter  (`LRO`_) mission has gathered some
fantastic data of the lunar surface  and, thanks to `NASA`_, all are
available for free on the internet.

However, using them can be cryptic  without a bit of experience.  This
library aims to facilitate the extraction of knowledge from two set of
data gathered by two experiments on board of LRO:

   - The Lunar Orbiter Laser Altimeter (`LOLA`_) experiment which
     collected high resolution topographic data of the lunar surface 
   - The  Lunar  Reconnaissance  Orbiter Camera  (`LROC`_)  experiment
     which collected images of the lunar surface. In particular, we
     focus on Wide Angle Images taken from the Wide Angle Camera (`WAC`_)


Highlighted features
------------------------

Unlike  previous python  PDS  library, this  module  allows to  easily
extract  part of  a PDS  image without  loading the  whole thing  into
memory  (Sizes  can  be  up  to  Gigabytes).   Great  for  looking  at
geological unit  on the Moon.  Include some extension to  study impact
crater and lunar domes specifically.

Contents:
---------

.. toctree::
   :maxdepth: 2

   install
   cookbook
   PDS_Extractor
   Structure
   support

.. _NASA:
    https://pds.nasa.gov/

.. _LOLA:
    http://lunar.gsfc.nasa.gov/lola/

.. _LRO:
    http://www.nasa.gov/mission_pages/LRO/main/index.html

.. _LROC:
    http://lroc.sese.asu.edu/about
    
.. _WAC:
    http://lroc.sese.asu.edu/images
    
Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

