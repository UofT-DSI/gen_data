# Setup
## Environment Setup Guide
Before using this repo, complete the relevant steps in the [environment setup guide](https://github.com/UofT-DSI/onboarding/tree/main/environment_setup/os_guides), which installs the core tools you’ll need for this module:

- Visual Studio Code
- Git  
- Git Bash (for Windows)
- Quarto
- R
- PLINK2

## R Packages to Install (Run Once) 
Open a Terminal and install the required packages:

```bash
R --vanilla -e "cran_packages <- c('data.table','ggplot2','seqminer','HardyWeinberg','dplyr','qqman','knitr','metafor'); missing <- setdiff(cran_packages, rownames(installed.packages())); if (length(missing)) install.packages(missing, repos='https://cloud.r-project.org')"
```

These packages cover the tutorials and assignment workflows in this repository.

## Notes
- This module uses command-line tools (especially `plink2`) in addition to R.
- Tutorials and assignments use `.qmd` files, so Quarto should be installed and available.

## Test Your Setup
Run these checks from the repository root to confirm your environment is ready.

1. Verify command-line tools:

```bash
quarto --version
R --version
plink2 --version
```

2. Verify required R packages:

```bash
R --vanilla -e "pkgs <- c('data.table','ggplot2','seqminer','HardyWeinberg','dplyr','qqman','knitr','metafor'); missing <- setdiff(pkgs, rownames(installed.packages())); if (length(missing)) { cat('Missing packages:\\n'); print(missing); quit(status = 1) } else { cat('All required packages are installed.\\n') }"
```

3. Run a Quarto smoke test (no external data required):

```bash
printf '%s\n' '---' 'title: "setup-smoke-test"' 'format: html' '---' '' '```{r}' '1 + 1' '```' > setup_smoke_test.qmd
quarto render setup_smoke_test.qmd
```

If all checks pass without errors, your setup is complete.

For questions or issues, contact the learning support team or email `courses.dsi@utoronto.ca`.
