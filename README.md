
---
# CAnD3 Reproducible Research Project - GSS 2017

## Project Overview

This study explores disparities in self-rated mental health among young adults (aged 18-39) in Canada using data from the 2017 General Social Survey (Cycle 31): Family. The repository contains the R scripts required to reproduce the analysis, including data cleaning, descriptive statistics, and regression analysis.


## Data Description

The data used in this study comes from the 2017 General Social Survey (Cycle 31): Families, Statistics Canada's Public Use Microdata Files (PUMFs) obtained through ODESI, a service provided by the Ontario Council of University Libraries.

Access to ODESI is restricted to users with a DLI License, and it can be used for statistical and research purposes. The terms of the license can be found [here](https://www.statcan.gc.ca/eng/about/research/data/odc-dli).

McGill University's CAnD3 initiative has a license to use the data for training purposes. Those outside McGill University should not use the data provided through CAnD3's training activities for purposes unrelated to CAnD3 training. Those from another DLI institution should download the data using ODESI through their institution.

## Codebook

The codebook for this data is publicly available through ODESI at: [https://odesi.ca/](https://odesi.ca/)

## Data Citation

- Statistics Canada. 2020. General Social Survey, Cycle 31, 2017 [Canada]: Family (version 2020-09). Statistics Canada [producer and distributor], accessed September 10, 2021. ID: gss-12M0025-E-2017-c-31.

## Files Included 


| **File**                              | **Description**                                          |
|---------------------------------------|----------------------------------------------------------|
| **Files.zip**                         | Zip folder containing all project files.           |
| **Instructions for Reproducing Analysis.Rmd** | RMarkdown file with instructions for reproducing the analysis. |
| **Code for Data Wrangling.R**         | R script for data recoding and handling missing cases.    |
| **Code for Descriptive_Statistics.R** | R script for generating descriptive statistics.           |
| **Code for Logistic Regression.R**    | R script for chi-square tests and logistic regression.    |
| **README.md**                         | Project overview.                                         |
| **Reproducible Research_GSS2017.Rproj** | R project file.                                           |

## Instructions for Reproducing the Analysis

For detailed instructions on how to reproduce the analysis, including how to download the dataset and run the R scripts, please refer to the `Instruction for Reproducing Analysis.Rmd` file available in this repository.The instruction file will guide you through running the R Scripts for data cleaning, descriptive statistics, and logistic regression.

---

## Software Requirements


- `R` and `RStudio`

### Required R Packages

- `tidyverse`
- `sjPlot`

To install the required R packages, run:

```r
install.packages(c("tidyverse", "sjPlot"))
```

---

## System Information

- `Operating System`: Darwin 23.6.0 (macOS)
- `Kernel Version`: Darwin Kernel Version 23.6.0
- `Memory`: 16 GB
- `Processor`: ARM64

### R Version

- **R Version**: R version 4.4.1 (2024-06-14)

## License


---

