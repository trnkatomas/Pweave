.. image:: https://zenodo.org/badge/doi/10.5281/zenodo.44683.svg
   :target: http://dx.doi.org/10.5281/zenodo.44683
.. image:: https://travis-ci.org/mpastell/Pweave.svg?branch=master
   :target: https://travis-ci.org/mpastell/Pweave
.. image:: https://coveralls.io/repos/github/mpastell/Pweave/badge.svg?branch=master
   :target: https://coveralls.io/github/mpastell/Pweave?branch=master


About Pweave
-------------

Pweave is a scientific report generator and a literate programming
tool for Python. Pweave can capture the results and plots from data
analysis and works well with NumPy, SciPy and matplotlib. It is able to run
python code from source document and include the results and capture
`matplotlib <http://matplotlib.sourceforge.net/>`_ plots in the output.

It can produce reST, Sphinx, Latex, HTML and markdown (pandoc and leanpub)
output from several input formats.

- Noweb  uses `noweb <http://www.cs.tufts.edu/~nr/noweb/>`_ syntax for separating code from documentation.
- Markdown. Run code from markdown code blocks.
- Script. Python script with special markup in comments.

Pweave is good for creating reports, tutorials, presentations etc. with embedded python
code It can also be used to make websites together with e.g. Sphinx or rest2web.

Features:
---------

* Python 2.7, 3.4 and 3.5 compatibility
* **Execute python code** in the chunks and **capture** input and output to a report.
* **Use hidden code chunks,** i.e. code is executed, but not printed in the output file.
* Capture matplotlib graphics.
* Evaluate inline code in documentation chunks marked using ``<% %>`` and ``<%= %>``.
* Cache all code and results from previous runs for fast report
  generation when you are only working with documentation. Inline code
  will be hidden in documentation mode.
* Supports reST, LaTeX, HTML or markdown for document chunks
* Publish reports from Python scipts. Similar to R markdown.
* Run from command line or interpreter.
* Support also for Octave and Matlab code.

Install
-----------------------

**Note: pip install fails in Python 3 due to a bug in pip. You'll need to use one of the other options.**

From PyPi::

  pip install --upgrade Pweave

or::

  easy_install -U Pweave

with conda::

  conda config --add channels mpastell
  conda install pweave

or download the source and run::

  python setup.py install


Pweave documentation can be found from the website http://mpastell.com/pweave


Release Notes
-------------

See `GHANGELOG.txt <https://github.com/mpastell/Pweave/blob/master/CHANGELOG.txt>`_ for changes in each release.

License information
-------------------

See the file "LICENSE" for information on the history of this
software, terms & conditions for usage, and a DISCLAIMER OF ALL
WARRANTIES.
