---
title: Building National Geospatial Datasets
summary: Developing open, high-resolution national datasets on the built environment and housing to support research on environmental hazards and health.
date: 2026-10-15
tags:
  - Open Data
  - Built Environment
  - Housing
image:
  caption: 'Figure from Ahn et al. (2024), Scientific Data'
---

Many questions about environmental hazards and health need detailed, consistent data on where people live and what their homes are like, but national data are often coarse, incomplete, or limited in time. I build open, national-scale geospatial datasets by integrating property-level, parcel, census, and remote sensing data, and I share the data and code so others can use them.

## Example projects

### Residential air conditioning prevalence across the United States

A property-level dataset of residential air conditioning covering more than 103 million housing units in the contiguous U.S. Machine learning models (XGBoost) impute four AC types from housing characteristics, socioeconomic indicators, and environmental conditions. The dataset is summarized at census tract and ZIP code levels, with county and metropolitan summaries, to support research on heat exposure and adaptation.

- Paper: Ahn, Y. & Uejio, C. K. (2025). [A Comprehensive Dataset of Residential Air Conditioning Prevalence in the Continental United States](https://www.nature.com/articles/s41597-025-06104-3). *Scientific Data*.
- [Data](https://doi.org/10.7910/DVN/A0CGTX) · [Code](https://github.com/YoonjungAhn/NationwideAC)

### HISDAC-US: Historical Settlement Data Compilation for the United States

Version 2 of HISDAC-US, an attribute-rich sequence of gridded settlement layers spanning 200 years (1810–2020) for the contiguous U.S. It integrates property-level real estate, parcel, and remote sensing-based building footprint data, and includes land use and structural information as of 2021. The data support studies of urban form, natural hazard risk, population modeling, land use, and health.

- Paper: Ahn, Y., Leyk, S., Uhl, J. H. & McShane, C. M. (2024). [An Integrated Multi-Source Dataset for Measuring Settlement Evolution in the United States from 1810 to 2020](https://www.nature.com/articles/s41597-024-03081-x). *Scientific Data*.
- [Data](https://dataverse.harvard.edu/dataverse/hisdac-usv2) · [Code](https://github.com/YoonjungAhn/HISTPLUS)
