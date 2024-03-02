# Lipidomics Data Post-Processing in R

*CDM5104 Project Work*

## Summary

In this project, you will go through some steps of a lipidomics data processing workflow using R with [tidyverse](https://www.tidyverse.org) packages. The example dataset used in the project was obtained from Tan et al. '*Variability of the Plasma Lipidome and Subclinical Coronary Atherosclerosis*' [DOI: 10.1161/atvbaha.121.316847](https://doi.org/10.1161/atvbaha.121.31684)

You will inspect and process this targeted mass spectrometry (MS)-based plasma lipidomics raw dataset, starting from peak areas, moving to data quality control and ending with a table of QC-filtered lipid concentration values.

## 2. Installing R and RStudio

If you have these programs already installed on your computer, please ensure that you have R Version 4.1 or higher, and RStudio Version 2022.02 or higher installed. Otherwise, or if you have not yet installed them, proceed with following sequence:

1.  R: Download from [https://cloud.r-project.org](https://cloud.r-project.org/){.uri}

2.  RStudio: download from [https://posit.co/download/rstudio-desktop](https://posit.co/download/rstudio-desktop/){.uri}

## 3. Installing R packages

Please install following packages by running following code in your R console:

``` r
# CRAN packages
install.packages(c("here", "tidyverse", "broom", "ggrepel", "ggpmisc"))

# Bioconductor packages
if (!require("BiocManager", quietly = TRUE)) install.packages("BiocManager") 
  BiocManager::install(c("rgoslin"))
```

## 4. Download and run the RStudio project

Download the R Project containing the scripts and data used for project work from this repository (click on the green button "\<\>Code" and then "Download ZIP"). Alternatively, you can clone this repository using RStudio or Git. Do not hesitate to contact us if you have any questions. Double-click the <CDM5104_Lipidomics.Rproj> file to open  the project in RStudio. (Do not just open the CDM5104_Project.qmd file)

## 5. Author

-   Bo Burla - [Singapore Lipidomics Incubator](https://sling.sg) \@ NUS

## 6. Acknowledgments

-   Authors of the dataset used in this project work: Tan et al., *Atheroscler Thromb Vasc Biol*, 2021 [DOI: 10.1161/atvbaha.121.316847](https://doi.org/10.1161/atvbaha.121.31684)
-   Members of the Singapore Lipidomics Incubator

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
