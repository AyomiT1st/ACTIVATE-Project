# ACTIVATE-Project
# ACTIVATE Aerosol and Cloud Analysis

Analysis workflows and supporting code for aerosol, cloud water, and air-mass characterization using data from the NASA ACTIVATE campaign over the Northwest Atlantic.

## Overview

This repository contains code and analysis workflows developed for research using observations from the **Aerosol Cloud meTeorology Interactions oVer the western ATlantic Experiment (ACTIVATE)**. The work focuses on understanding aerosol properties, cloud water composition, source influences, transport pathways, and related atmospheric processes over the western North Atlantic and the U.S. East Coast outflow region.

The project includes analyses related to:

- cloud water chemical composition
- aerosol size distributions
- CCN and activation behavior
- source apportionment using PMF
- air-mass trajectory analysis
- concentration-weighted trajectory (CWT) analysis
- statistical and visualization workflows for airborne atmospheric measurements

## Scientific Goals

The broader goals of this project are to:

- characterize the chemical and physical properties of aerosols and cloud water sampled during ACTIVATE
- identify major source influences on observed atmospheric composition
- evaluate how transport patterns affect aerosol and cloud water properties
- investigate relationships among aerosol composition, size, cloud processing, and regional outflow

## Data Sources

This repository works with datasets derived from ACTIVATE airborne observations, which may include:

- cloud water composition measurements
- aerosol chemical species
- aerosol number and size distribution data
- CCN-related variables
- trace gas and meteorological variables
- flight location and time information
- back trajectories generated with HYSPLIT

Some datasets may be processed or merged products prepared for analysis.

## Main Methods

Methods used in this repository may include:

- **data cleaning and QA/QC**
- **time alignment and dataset merging**
- **descriptive statistics**
- **source apportionment with EPA PMF**
- **trajectory analysis with HYSPLIT**
- **concentration-weighted trajectory (CWT) analysis**
- **correlation and regression analysis**
- **cluster analysis**
- **visualization of spatial, temporal, and chemical patterns**

## Repository Structure

Example structure:

```text
ACTIVATE/
├── data/
│   ├── raw/                  # raw input data (not typically tracked on GitHub)
│   ├── processed/            # cleaned or merged datasets
│   └── external/             # auxiliary files, metadata, trajectories
├── notebooks/                # Jupyter notebooks for exploration and plotting
├── scripts/                  # Python scripts for processing and analysis
├── figures/                  # exported figures
├── outputs/                  # tables, summaries, model outputs
├── docs/                     # notes, references, manuscript support files
├── environment.yml           # conda environment file
├── requirements.txt          # Python dependencies
└── README.md
