# Predicting avoidable ED visits using the MIMIC-IV-ED database

This is an analysis of the MIMIC-IV-ED database. The results of the analysis can be found here (PREPRINT LINK TO BE ADDED).

## Instructions
To reproduce this analysis, follow these steps in order. 

1. Clone (or download as a zip) this repo, and reopen the readme.md locally
    - The kernel I used to run this analysis was R 4.5.0
    - The necessary packages are installed and loaded using the R package "pacman" at the start of the notebooks

2. First, the MIMICED data for this analysis must be created using the [MIMICED](https://github.com/James-G-Wrightson/MIMICED.git) repo, which included  as a submodule of this repo. 
    - Instructions for creating the data can be found in the [readme](https://github.com/James-G-Wrightson/MIMICED/blob/main/README.md) file for that repo.
    - When you clone this current repo, the submodule will be available in a folder called MIMICED

3. Once the data are created, the [prediction](PREDICTION/3_prediction.ipynb) notebook can be run. 
    - The kernel used to run this notebook was Python 3.10.18
    - The requirements.txt lists the relevant libraries and versions