# Ground Motion Displacement RMS vs Time

*an example simple tutorial for getting seismic data, computing the power spectral densities, extracting the RMS and plotting*

[![DOI](https://zenodo.org/badge/doi/10.5281/zenodo.3820046.svg)](http://dx.doi.org/10.5281/zenodo.3820046)

Required:

- python
- obspy (and its dependencies)
- pandas
- jupyter
- notebook
- tqdm

this should be easy to set up in a conda env: ``conda create -c conda-forge -n covid python=3.7 obspy pandas jupyter notebook tqdm``

Author: Thomas Lecocq @seismotom, Fred Massin @fmassin

Run it interactively on [mybinder.org](https://mybinder.org/v2/gh/ThomasLecocq/SeismoRMS/master)


## Example:
The following data shows the effect of the Social Distancing measures from the
Belgian Government (2020-03-16 at midnight, and 2020-03-18 at midday):

![Example image from this code:](covid-19_ucc.png)
