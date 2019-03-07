# Evidence for model-based encoding of Pavlovian contingencies in the human brain

> The article describing this study is available at: [https://doi.org/10.1038/s41467-019-08922-7](https://doi.org/10.1038/s41467-019-08922-7)

The repository contains all scripts needed to reproduce the results reported in the above study. 

## Data

You will of course need the data in order to reproduce these results. The data are on OSF: [http://dx.doi.org/10.17605/OSF.IO/CHFNW](http://dx.doi.org/10.17605/OSF.IO/CHFNW).

## Code

The code is split in two folders for *preprocessing* and *mvpa*:
- [./preprocessing](preprocessing) - custom-built nipype pipeline for preprocessing anatomical data
- [./mvpa](mvpa) - script for reproducing MVPA results
  - [./mvpa/striatum](mvpa/striatum) - scripts for striatal mvpa
  - [./mvpa/cortex](mvpa/cortex) - scripts for cortical mvpa


**Note:** This repository is still incomplete, as I am preparing these scripts so that they can be run in the cloud. Please report any issues you encounter.
