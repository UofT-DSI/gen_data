# Setup
## Environment Setup Guide
Before using this repo, make sure you’ve completed **parts** of the the [environment setup guide](https://github.com/UofT-DSI/onboarding/tree/main/environment_setup/os_guides), which installs the core tools you’ll need for this module, specifically:

- Visual Studio Code
- Git  
- Git Bash (for Windows)
- Quarto
- R
- PLINK

## R Packages to Install (Run Once) 
Open a Terminal and install the required packages:

```
R --vanilla -e "cran_packages <- c('data.table','ggplot2','HardyWeinberg','dplyr','qqman','genio','Matrix','quarto'); dir.create(Sys.getenv('R_LIBS_USER'), showWarnings = FALSE, recursive = TRUE); install.packages(setdiff(cran_packages, rownames(installed.packages())), repos='https://cloud.r-project.org', lib=Sys.getenv('R_LIBS_USER'))"
```

These packages cover the tutorials and assignment workflows in this repository.

## Notes
- Run all cells in `test.qmd` to verify that the installation completed successfully.
- This module uses command-line tools (especially `plink2`) in addition to R.
- Tutorials and assignments use `.qmd` files, so Quarto should be installed and available.

For questions or issues, contact the learning support team or email `courses.dsi@utoronto.ca`.
