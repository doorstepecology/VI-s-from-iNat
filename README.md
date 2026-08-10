Doorstep Ecology VI Score Calculator

An R-based tool designed to calculate Vegetation Integrity (VI) scores for plant communities using observations exported from iNaturalist, aligned with the NSW Biodiversity Assessment Method (BAM).

***this repo is a work-in-progress,  and will be updated asap. A couple of key files are yet to be published. For updates contact doorstepecology@gmail.com

📄 Overview

This project provides an automated workflow in R to:

Standardize iNaturalist observation data and annotate them with NSW bionet growth form groups
Compute Vegetation Integrity (VI) scores on the above using NSW BAM calculation formulas.

🛠️ Requirements & Setup Prerequisites

An iNaturalist account, or a copy of the data export
R with tidyverse

Data Inputs:
observations-*.csv: Exported iNaturalist observations (please note, the observations need to be annotated with observation fields in line with a specific methodology)
bionet-native-species-by-growth-form-data.csv: Native species growth form dataset sourced from NSW BioNet.
CSVExport_PCT_Benchmarks_Export_*.csv: PCT benchmark attributes sourced from NSW BioNet.


⚖️ License & Data Attribution Code License

The R code and scripts in this repository are available under the MIT License. Data Sources & Attribution

Benchmark datasets and species growth form data are sourced from NSW BioNet (NSW Department of Climate Change, Energy, the Environment and Water) and used under the Creative Commons Attribution 4.0 International (CC BY 4.0) license.

Likewise the vegetation integrity concept and calculation method is derived from the NSW Biodiversity Assessment Method (https://www.environment.nsw.gov.au/publications/biodiversity-assessment-method-2020) (NSW Department of Climate Change, Energy, the Environment and Water) and used under the Creative Commons Attribution 4.0 International (CC BY 4.0) licence.

Field observation data processed by this tool originates from user submissions on iNaturalist. The specific licence for the observation data is listed per observation in the data export csv,  in general these are CC-BY-NC
