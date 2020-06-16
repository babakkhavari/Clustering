[![DOI](https://zenodo.org/badge/253060700.svg)](https://zenodo.org/badge/latestdoi/253060700)

# Clustering
Script and data from: **Clusters in action - Assessing the urban-rural split and electrification in Sub-Saharan Africa** by Babak Khavari, Alexandros Korkovelos, Andeas Sahlberg, Francesco Fuso-Nerini and Mark Howells. Datasets produced using the method described in the paper are available at: https://data.mendeley.com/datasets/z9zfhzk8cr.

## Content
This repository contains:
* An environment .yml file needed for generating a fully functioning python 3.7 environment necessary for the clustering algorithm.
* The clustering code and related functions
* An example case for Benin

## Setting up the environment & running the model

**Install from GitHub**

Download repository directly or clone it to you designated local directory using:

```
git clone https://github.com/babakkhavari/Clustering.git
```

**Requirements**

The clustering module (as well as all supporting scripts in this repo) have been developed in Python 3. We recommend installing [Anaconda's free distribution](https://www.anaconda.com/distribution/) as suited for your operating system. 

Once installed, open anaconda prompt and move to your local "clustering" directory using:

```
> cd ..\clustering
```

In order to be able to run the clustering tool (main.ipynb and funcs.ipynb) you have to install all necessary packages. "full_project.yml" contains all of these and can be easily set up by creating a new virtual environment using:

```
conda env create --name clustering --file full_project.yml
```

This might take some time. When complete, activate the virtual environment using:

```
conda activate clustering
```

With the environment activated, you can now move to the clustering directory and start a "jupyter notebook" session by simply typing:

```
..\clustering> jupyter notebook 
```
## Changelog

## Resources
Original dataset can be found here: https://data.mendeley.com/datasets/z9zfhzk8cr/

Journal article can be found here:
## Credits

**Conceptualization:** [Babak Khavari](https://github.com/babakkhavari) & [Francesco Fuso-Nerini](https://github.com/FFusoNerini)<br />
**Methodology:** [Babak Khavari](https://github.com/babakkhavari)<br />
**Software:** [Babak Khavari](https://github.com/babakkhavari)<br />
**Validation:** [Babak Khavari](https://github.com/babakkhavari), [Alexandros Konrkovelos](https://github.com/akorkovelos) & [Andreas Sahlberg](https://github.com/AndreasSahlberg)<br />
**Supervision, Review and Advisory support:** [Francesco Fuso-Nerini](https://github.com/FFusoNerini) & [Mark Howells](https://orcid.org/0000-0001-6419-4957)<br />
**Funding:** The World Bank (contract number: 7185716), [KTH](https://www.kth.se/en/itm/inst/energiteknik/forskning/desa/welcome-to-the-unit-of-energy-systems-analysis-kth-desa-1.197296)
