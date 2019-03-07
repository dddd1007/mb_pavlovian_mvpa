# Evidence for model-based encoding of Pavlovian contingencies in the human brain

> DOI: [https://doi.org/10.1038/s41467-019-08922-7](https://doi.org/10.1038/s41467-019-08922-7)

**Note:** This repository is still incomplete, as I am preparing these scripts so that they can be run in the cloud. Please report any issues you encounter.

The repository contains all scripts needed to reproduce the results presented in the above study. 

## Data

In order to reproduce these results, you will of course need the data, which is stored on OSF: [http://dx.doi.org/10.17605/OSF.IO/CHFNW](http://dx.doi.org/10.17605/OSF.IO/CHFNW).

## Code

The code is split in two folders:
- [./preprocessing](preprocessing) - custom-built nipype pipeline for preprocessing anatomical data
- [./mvpa](mvpa) - script for reproducing MVPA results
  - [./mvpa/striatum](mvpa/striatum) - scripts for striatal mvpa
  - [./mvpa/cortex](mvpa/cortex) - scripts for cortical mvpa
