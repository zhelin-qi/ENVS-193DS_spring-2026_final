# ENVS-193DS_spring-2026_final

## General information

This repository contains the final assignment for ENVS 193DS (Spring 2026) at UC Santa Barbara.

**Author:** Zhelin Qi  
**Date:** June 9, 2026  
**Course:** ENVS 193DS — Statistics for Environmental Studies

This assignment includes three problems:
- **Problem 1:** Research writing — identifying statistical tests and improving scientific communication
- **Problem 2:** Data analysis — modeling the effects of tree height and acacia ant species on bird nest occurrence using binomial generalized linear models
- **Problem 3:** Affective and exploratory visualizations — analyzing personal dog satisfaction data using Pearson correlation

## Data and file overview

```
ENVS-193DS_spring-2026_final/
├── README.md
├── code/
│   └── ENVS-193DS_spring-2026_final.qmd   # main Quarto document
└── data/
    ├── nest_data_final.csv                 # nest box occupancy data (Lujan et al. 2023)
    └── dog_satisfaction_data.csv           # personal dog satisfaction data (Zhelin Qi, 2026)
```

**nest_data_final.csv**  
Source: Lujan, E., Nielsen, R., Short, Z., Wicks, S., Nderitu Watetu, W., Malingati Khasoha, L., Palmer, T. M., Goheen, J. R., & Alston, J. M. (2023). Data, code, and metadata for: Symbiotic acacia ants drive nesting behavior by birds in an African savanna [Data set]. Zenodo. https://doi.org/10.5281/zenodo.8373322  
Key variables used: `case_control` (1 = nest present, 0 = nest absent), `height_cm` (tree height in cm), `ant_species` (acacia ant species identity)

**dog_satisfaction_data.csv**  
Source: Personal data collected by Zhelin Qi, April 17–30, 2026  
Key variables: `playtime_minutes` (daily playtime duration in minutes), `dog_satisfaction_level_1_5` (post-play satisfaction score 1–5), `leash_status` (on-leash or off-leash)

## Rendered output

The rendered PDF is available here: [ENVS-193DS_spring-2026_final.pdf](https://github.com/zhelin-qi/ENVS-193DS_spring-2026_final/blob/main/code/ENVS-193DS_spring-2026_final.pdf)
