# Systematic_Review_for_Psychologists <img src="https://media.giphy.com/media/1oGT95WukVFcRO1OFZ/giphy.gif" width="50">

[![](https://img.shields.io/badge/Language-R-blue)](http://cran.r-project.org/)

<sub>*Last updated 2024-03-21.*</sub>

This GitHub repository contains R code for conducting a Systematic Review, specifically tailored for psychologists. In the first stage of the systematic review is to download references from databases such as 'PyscInfo', 'PsycArticles', 'Scopus', 'MEDLINE'. Traditionally, students and researchers manually organise these references, removing duplicates and screening for relevance by reading titles and abstracts. Using the `revtools` package in R simplifies these tasks with a user-friendly interface. It also offers machine learning tools to visualise patterns in the data, allowing researchers to interactively select or exclude references, words, or topics based on these visualisations.

As there isn't much online discussion about this helpful tool, I've created a user guide outlining how to utilise some of the functions in R, with the hope of saving you time and enhancing your research efficiency!

**Systematic Review (Article Screening; Data Wrangling), using [`revtools`](https://cran.r-project.org/web/packages/revtools/index.html)**. 
## :telescope: Overview

The repository is organised into the following sections:

- **[01 User Guide](/R/01_Power_Analysis.R)**: User Guide for running the `revtools` package for titles and abstracts screening.
- **[02 Data Files](/R/02_SEM_Model_Assumptions.R)**: Two data files to practicing using the package mentioned in the user guide.

## :scroll: Notes

This repository assumes basic competence in R (setting working directory, loading packages, etc) and contains only materials relating to *Systematic Review in R*. So the focus will be generally on the application and not on the theory.  

## :hammer_and_wrench: Setup

To run the code, you will need:

1. The data files relating to your literature search, downloaded from your chosen database(s).
2. Your inclusion and exclusion criteria for your systematic review.
3. A fresh installation of [**`R`**](https://cran.r-project.org/) (preferably version 4.3.2 or above).
4. [RStudio IDE](https://www.rstudio.com/products/rstudio/download/) (optional but recommended).
5. Install the required packages by running:

   ```R
   # Load the package
   install.packages("revtools")
   ```

<details>
<summary>
<i>Package Versions</i>
</summary>
   
Run on Windows 11 x64 (build 22621), with R version 4.3.2.

The packages used here:

- `revtools` 0.4.1(*CRAN*)

</details>

Feel free to adjust this based on your preferences and specific details about your code and setup.
