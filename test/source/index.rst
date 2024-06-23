.. Test-project documentation master file, created by
   sphinx-quickstart on Tue Jun 18 23:09:05 2024.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to sphinx documentation
========================================
.. toctree contains basically the table of contents and how it must be appeared in a hirearchy level.
   When you create new topics, you must add them to a TOC in the project.
   the maxdepth tells us how many sub headings must appear inside a file
   captions are nothing but captions to the files
   numbered helps in making appear the content files in a numbered way
.. toctree::  
   :maxdepth: 1
   :numbered:

   00_Comments
   01_list_headers
   02_creating_hyperlink
   03_Coding.rst
   04_Link for another doc
   05_link section from index
   06_link for a section
   07_Note, warnings
   08_Tables
   09_images
   10_Glossary
   11_link to glossary
.. The above provided files are rst files. It is not necessary to provide .rst extension at the end




Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
