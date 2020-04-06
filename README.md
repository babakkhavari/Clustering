# Clustering
Script and data from: "xxxxx" by Babak Khavari, Alexandros Korkovelos, Andeas Sahlberg, Francesco Fuso-Nerini and Mark Howells

## Setting up the environment & running the model

Install from GitHub

Download repository directly or clone it to you designated local directory using:

git clone https://github.com/alekordESA/agrodem.git

Requirements

The agrodem module (as well as all supporting scripts in this repo) have been developed in Python 3. We recommend installing Anaconda's free distribution as suited for your operating system.

Once installed, open anaconda prompt and move to your local "agrodem" directory using:

> cd ..\agrodem

In order to be able to run the agrodem model (agrodem.ipynb) you should install all necessary packages. "agrodem_environment.ylm" contains all of these and can be easily set up by creating a new virtual environment using:

conda env create --name agrodem_run --file agrodem_environment.ylm

This might take a while.. When complete, activate the virtual environment using:

conda activate agrodem_run 

With the environment activated, you can now move to the agrodem directory and start a "jupyter notebook" session by simply typing:

..\agrodem> jupyter notebook 

Note 1 Use full_project_environment.yml under the same instructions to set up a supporting environment for all processes described in this repo.

Note 2 that pyeto is also needed and can be installed from https://github.com/woodcrafty/PyETo.git