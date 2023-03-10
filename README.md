# Introduction to geemap

Description

Google Earth Engine (GEE) is a cloud computing platform with a multi-petabyte catalog of satellite imagery and geospatial datasets. It enables scientists, researchers, and developers to analyze and visualize changes on the Earth’s surface. The geemap Python package provides GEE users with an intuitive interface to manipulate, analyze, and visualize geospatial big data interactively in a Jupyter-based environment. The topics to be covered in this workshop include:

- Introducing geemap and the Earth Engine Python API
- Creating interactive maps
- Searching GEE data catalog
- Displaying GEE datasets
- Classifying images using machine learning algorithms
- Computing statistics and exporting results
- Producing publication-quality maps
- Building and deploying interactive web apps, among others
This workshop is intended for scientific programmers, data scientists, geospatial analysts, and concerned citizens of Earth. The attendees are expected to have a basic understanding of Python and the Jupyter ecosystem. Familiarity with Earth science and geospatial datasets is useful but not required.

# Useful link
- GeoPython 2021 Conference website (https://2021.geopython.net/)
- Google Earth Engine (https://earthengine.google.com/)
- geemap.org (https://geemap.org/)

# Prerequisite
- A Google Earth Engine account. Sign up here if needed.
- Miniconda or Anaconda

# Set up a conda environment

- conda create -n geo python=3.8
- conda activate geo
- conda install geemap -c conda-forge
- conda install jupyter_contrib_nbextensions -c conda-forge
- jupyter contrib nbextension install --user

