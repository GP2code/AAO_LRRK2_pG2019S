# The age at onset of *LRRK2* p.Gly2019Ser Parkinson's disease across ancestries and countries of origin

`🦋 GP2 ❤️ Open Science 😍🦋`

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15367561.svg)](https://doi.org/10.5281/zenodo.15367561)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**Last Updated:** March 2025

## Summary

This is the online repository for the article  titled ***"The age at onset of LRRK2 p.Gly2019Ser Parkinson's disease across ancestries and countries of origin"***. 
The *LRRK2* p.Gly2019Ser pathogenic variant has reduced penetrance and presents with a wide range of age at onset (AAO) in patients with Parkinson's disease (PD). Herein, we aim to elucidate differences in the cumulative incidence of *LRRK2* p.Gly2019Ser-related PD (LRRK2-PD) between ancestries and countries.

## Data Statement

- All GP2 data are hosted in collaboration with the Accelerating Medicines Partnership in Parkinson's Disease and are available via application on the website. The GP2 PD case and control data are available via the GP2 website ([https://gp2.org](https://gp2.org); release 7: [https://doi.org/10.5281/zenodo.10962119](https://doi.org/10.5281/zenodo.10962119)). Genotyping imputation, quality control, ancestry prediction, and processing were performed using GenoTools (v1.0.0), publicly available on GitHub

## Helpful Links 
* [GP2 Website](https://gp2.org/)
    * [GP2 Cohort Dashboard](https://gp2.org/cohort-dashboard-advanced/)
* [Introduction to GP2](https://movementdisorders.onlinelibrary.wiley.com/doi/10.1002/mds.28494)
    * [Other GP2 Manuscripts (PubMed)](https://pubmed.ncbi.nlm.nih.gov/?term=%22global+parkinson%27s+genetics+program%22)


## Repository Orientation
* Analyses discussed in the manuscript can be found in this repository:
    * The 1st notebook, titled `00_LRRK2_var_extract_G2019S_r7_AJ`, contains codes we used to extract the  *LRRK2* G2019S SNP from the PLINK genotype file. The PLINK PED file with the genotypes was subsequently merged with the clinical metadata (e.g., disease status, age at onset for patients, biological sex).
    * The 2nd notebook, titled `01_LRRK2_G2019S_data_vis_r7`, contains codes that we used to analyze the associations of *LRRK2* G2019S variant carriers' AAO and ancestry group or country.
X
```bash
THIS_REPO
├── README.md
└── analyses
    └── GP2
        ├── 00_LRRK2_var_extract_G2019S_r7_AJ
        └── 01_LRRK2_G2019S_data_vis_r7
```



## Analysis Notebooks
*  Languages: Python, bash, and R

|**Directory** |     **Notebooks**       |                                 **Description**                          |
|:------------:|:-----------------------:|:------------------------------------------------------------------------:|
| `GP2/`       |`00_LRRK2_var_extract_G2019S_r7_AJ`     | Extracting LRRK2 G2019S genotype information |
| `GP2/`       |`01_LRRK2_G2019S_data_vis_r7`       | Analyzing associations between AAO and ancestries/countries                                       |


## Software


|       **Software**                | **Version(s)** |           **Resource URL**                                           |   **RRID**     |                                                               **Notes**                                               |
|:---------------------------------:|:--------------:|:--------------------------------------------------------------------:|:--------------:|:---------------------------------------------------------------------------------------------------------------------:|
| Python Programming Language       |3.10            |http://www.python.org/                                                | RRID:SCR_008394| pandas; numpy; seaborn; matplotlib; statsmodel; rpy2; used for general data wrangling/plotting/analyses                     |
|R Project for Statistical Computing|4.4.2           |http://www.r-project.org/                                             | RRID:SCR_001905| tidyverse; dplyr; tidyr; ggplot2; car; cowplot; grid; RColorBrewer; forestmodel; survival; used for general data wrangling/plotting/analyses|
|PLINK                              |1.9 and 2.0     |http://www.nitrc.org/projects/plink                                   | RRID:SCR_001757| used for genetic analyses                                                                                             |
---

