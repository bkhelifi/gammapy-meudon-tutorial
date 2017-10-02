# gammapy-meudon-tutorial
This repository aims to share instructions and material for the Tutorial taking place the 3rd October, 2017, in Meudon : https://indico.obspm.fr/event/22/

## I Objectives

The goal of this day is to make an introduction to data analysis by playing with real scripts explained by experts. 3 sessions are organised:
* a Fermi tutorial: *COSMAX*
* an introduction to python
* a CTA tutorial with the package *ctools*
* a CTA tutorial with the package *Gammapy*

All files can be downloaded on your computer by typing on a terminal :

`git clone https://github.com/bkhelifi/gammapy-meudon-tutorial.git`

A backup site is set up to download data used for the CTA tutorials:
https://www.dropbox.com/s/o4f5jczp42jjaw1/handson.zip?dl=0

For information, the open Data Format for gamma-ray astronomy is explained and described here:
http://gamma-astro-data-formats.readthedocs.io/en/latest/index.html .
This is a work in progress...

## II Introduction tutorial: *python* and *numpy*
This tutorial is driven by Régis Terrier (APC).

It uses the notebook : *notebooks/astropy_introduction.ipynb* and *notebooks/using_numpy.ipynb*

PS: to start a notebook, type on a terminal : `jupyter notebook toto.ipynb`

## III *COSMAX* : a Fermi tutorial 
This tutorial is driven by Benoît Lott (CENBG).

## IV *ctools* : a CTA tutorial
This tutorial is driven by Jürgen Knödlseder (IRAP).

## V *Gammapy* : a CTA tutorial
This tutorial is spitted in different part.

### V.1 General informations
Some useful links:
* Global documentation : http://docs.gammapy.org/en/latest/
* GitHub page: https://github.com/gammapy/gammapy 
    * Quick installation guide : http://docs.gammapy.org/en/latest/install/index.html 
* To receive news from the Gammapy team and developers, subscribe to the google groupe *gammapy* (https://groups.google.com/forum/#!forum/gammapy)
* You can contact the dev. team:
    * Christoph Deil : Christoph.Deil@mpi-hd.mpg.de
    * Bruno Khelifi : khelifi@in2p3.fr
    * Roberta Zanin : Roberta.Zanin@mpi-hd.mpg.de
    * Régis Terrer: terrier@apc.univ-paris7.fr

### V.2 Data Management
DataStore and links to HDU and OBS table, stacked observation

This tutorial is driven by Christoph Deil (MPIK Heidelberg).

It uses the notebook : *notebooks/tutorial_gammapy_intro.ipynb*

### V.3 Making a sky map
Counts maps, background estimation, excess and significance map, source fitting

This tutorial is driven by Yves Gallant (LUPM) and Fabio Acero (SAP).

It uses the notebook : *notebooks/tutorial_gammapy_maps.ipynb* *notebooks/cta_fit_sources_v2.ipynb*

### V.4 Making simulations and model fit
Simulation of fake data, 1D analysis for the background and spectrum, spectrum extraction, spectrum modelling and adjustment
 
This tutorial is driven by Julien Lefaucheur (LUTh).

It uses the notebook : *notebooks/tutorial_ebl.ipynb*

