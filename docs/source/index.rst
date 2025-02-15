.. Network_Analysis documentation master file, created by
   sphinx-quickstart on Fri Oct 25 19:20:53 2019.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Network_Analysis
================

A collection of useful scripts to analyse the local network and evaluate network speed and velocity

User Guide
^^^^^^^^^^

The Folder Data will contain all data that has been collected during the network tests (currently only ping test supported). All files that are stored in Data will not be deleted. Instead all new data will be appended to the existing existing file. Please make sure to not push your custom data collection to the GitRepo but include it in the .gitignore.

Starting Network Analysis
^^^^^^^^^^^^^^^^^^^^^^^^^

Currently there are different types of Network Analysis available. You can choose between a ping- and a speed test - both as .py files as well as .ipynb files. As a third option there is a small programm called network analysis which checks your ping at a custom intervall and depending on your ping time it then checks the actual speed of your internet connection. All results are again written in the Data folder from where they can be accessed and be used for further (statistical) tests. 

.. toctree::
   :maxdepth: 2

   license.rst

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
