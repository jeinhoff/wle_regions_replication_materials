# The length of working life in European regions: Disparities, divergence, and convergence between 2000 and 2024

Replication materials for the paper "The length of working life in European regions: Disparities, divergence, and convergence between 2000 and 2024" by Jan Einhoff and Christian Dudel.

## Code

- `00_download_data.Rmd`: national (HMD) and regional (Eurostat) life tables
- `01_preprocessing.Rmd`: preparation of the EU-LFS data
- `02_smoothing.Rmd`: smoothing of employment rates and working hours, bootstrap
- `03_estimation.Rmd`: working life expectancies
- `04_descriptives.Rmd`: tables and figures
- `05_decomposition.Rmd`: decomposition of changes in the standard deviation

The scripts read data from `data/` and write results to `outputs/`. They require R 4.1 or later.

## Data

The EU-LFS microdata can be requested from Eurostat and cannot be shared. The national life tables are available from the Human Mortality Database (www.mortality.org). All other data are downloaded from Eurostat in the scripts.

## Contact

Jan Einhoff, einhoff@demogr.mpg.de
