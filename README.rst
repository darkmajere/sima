.. image:: https://travis-ci.org/losonczylab/sima.svg?branch=master
   :target: https://travis-ci.org/losonczylab/sima/

.. image:: https://coveralls.io/repos/losonczylab/sima/badge.png 
   :target: https://coveralls.io/r/losonczylab/sima 

Overview
--------
SIMA (Sequential IMage Analysis) is an Open Source package for 
analysis of time-series imaging data arising from fluorescence
microscopy.  The functionality of this package includes:

- correction of motion artifacts
- segmentation of imaging fields into regions of interest (ROIs)
- extraction of dynamic signals from ROIs

The included ROI Buddy software provides a graphical user interface
(GUI) supporting the following functionality:

- manual creation of ROIs
- editing of ROIs resulting from automated segmentation
- registration of ROIs across separate imaging sessions


Installation and Use
--------------------
For complete documentation go to <http://www.losonczylab.org/sima>


Dependencies
-------------

* `Python <http://python.org>`_ 2.7 
* `numpy <http://www.scipy.org>`_ >= 1.6.2
* `scipy <http://www.scipy.org>`_ >= 0.13.0
* `matplotlib <http://matplotlib.org>`_ >= 1.2.1
* `scikit-image <http://scikit-image.org>`_ >= 0.9.3
* `shapely <https://pypi.python.org/pypi/Shapely>`_ >= 1.2.14

Optional dependencies
---------------------

* `OpenCV <http://opencv.org>`_ >= 2.4.8, required for segmentation,
  registration of ROIs across multiple datasets, and the ROI Buddy GUI
* `scikit-learn <http://scikit-learn.org>`_ >= 0.11, required for stICA
  segmentation
* `h5py <http://http://www.h5py.org>`_ >= 2.3.1, required for HDF5 file format
* `pylibtiff <https://code.google.com/p/pylibtiff/>`_, required for more
  efficient handling of large TIFF files
* `bottleneck <sima.ROI://pypi.python.org/pypi/Bottleneck>`_ >=0.8 , for faster
  performance
* `mdp <http://mdp-toolkit.sourceforge.net>`_, required for ICA demixing of
  channels

If you build the package from source, you may also need:

* `Cython <http://cython.org>`_


Citing SIMA
-----------
If you use SIMA for your research, please cite the following paper in any 
resulting publications:

  `Kaifosh P, Zaremba J, Danielson N, and Losonczy A. SIMA: Python software for
  analysis of dynamic fluorescence imaging data. Frontiers in Neuroinformatics.
  2014 Aug 27; 8:77. doi: 10.3389/fninf.2014.00077.
  <http://journal.frontiersin.org/Journal/101928>`_

License
-------
Unless otherwise specified in individual files, all code is

Copyright (C) 2014  The Trustees of Columbia University in the City of New York.

This program is free software; you can redistribute it and/or
modify it under the terms of the GNU General Public License
as published by the Free Software Foundation; either version 2
of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
