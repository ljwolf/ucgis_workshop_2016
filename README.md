PySAL UCGIS Workshop 2016
==========================
Serge Rey

Levi Wolf

May 23, 2016
Scottsdale, AZ 

[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org/repo/ljwolf/ucgis_workshop_2016)

This workshop will cover effective methods for spatial data processing,
analysis, visualization, and documentation of results. In addition, the workshop
will cover how to use well-known Python packages for data analysis, like Pandas
& IPython/Jupyter, with PySAL. Some up-and-coming packages that make spatial
data analysis workflows easier will also be introduced. Participants will learn
how to conduct a full exploratory spatial analysis workflow in this workshop

Requirements
----------------------
We request that attendees bring their own laptop. In addition, we ask that all
attendees install the following python software packages before attending the
workshop:

- PySAL 1.11
- Pandas
- Numexpr
- SciPy
- Numpy
- Jupyter Notebook
- Seaborn

Installation Instructions:
--------------------------

- Download and install Python 2.7 from [Anaconda](https://www.continuum.io/downloads). If you are on Windows, please install the 32-bit version. 
- Open Terminal.app (Mac) or Powershell (Windows)
- At the prompt, make sure your installation is up to date by running the
  command: `conda update conda`. directions. Press y if asked to confirm.
- Next, run `conda update mkl scipy numpy`.
- Once that finishes, install the dependencies required for the workshop by
  running `conda install pandas numexpr seaborn`.
- Then, run `pip install -U pysal` and confirm if asked.
- After `pysal` is installed, please run the following:
    - `pip install -U folium`
    - `pip install -U geojson`
- Finally, run `conda update jupyter`

Verifying Your Installation:
-----------------------------
At the same prompt you used to set up your terminal, type: `ipython` and hit
enter. It may take a second, but a new prompt should start. This is the ipython
& jupyter command-line interface. To make sure your environment is configured
correctly, run each of these commands at the interpreter:
- `import scipy.stats`
- `import numpy`
- `import pysal`
- `import pandas`
- `import numexpr`
- `import matplotlib`
- `import seaborn`

For windows users, if the first command fails with a message like : `DLL load
failed. The specified module could not be found`, please uninstall Anaconda and
be sure to install the 32-bit version. 

Virtual Machine instructions:
--------------------------------

Instructors:
-------------
Sergio J. Rey is Professor of Geographical Sciences and core faculty member of
the GeoDa Center of Geospatial Analysis and Computation at Arizona State
University.  He is a Fellow of the Spatial Econometrics Association. Dr. Rey is
project director for PySAL and the creator of the open source package STARS:
Space-Time Analysis of Regional Systems.


Levi John Wolf is a PhD candidate in the GeoDa Center of Geospatial Analysis and
Computation at Arizona State University. His focus is in spatial statistics for
polimetrics and quantitative social science. He has also consulted on statistics
and geospatial software engineering for startups, like CartoDB and Nextdoor.
