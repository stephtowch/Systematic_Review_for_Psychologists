# Systematic_Review_for_Psychologists <img src="https://media.giphy.com/media/1oGT95WukVFcRO1OFZ/giphy.gif" width="50">

[![](https://img.shields.io/badge/Language-R-blue)](http://cran.r-project.org/)

<sub>*Last updated 2024-03-21.*</sub>

This GitHub repository contains R code for conducting a Systematic Review, specifically tailored for psychologists. In the first stage of the systematic review is to download references from databases such as 'PyscInfo', 'PsycArticles', 'Scopus', 'MEDLINE'. Traditionally, students and researchers manually organise these references, removing duplicates and screening for relevance by reading titles and abstracts. Using the `revtools` package in R simplifies these tasks with a user-friendly interface. It also offers machine learning tools to visualise patterns in the data, allowing researchers to interactively select or exclude references, words, or topics based on these visualisations.

As there isn't much online discussion about this helpful tool, I've created a user guide outlining how to utilise some of the functions in R, with the hope of saving you time and enhancing your research efficiency!

**Systematic Review (Article Screening; Data Wrangling), using [`revtools`](https://cran.r-project.org/web/packages/revtools/index.html)**. 
## :telescope: Overview

The repository is organised into the following sections:

- **[1.0 User Guide](/1.0_User_Guide_Systematic_Review)**: This is a user guide for using the `revtools` package for titles and abstracts screening, as well as some data wrangling.
- **[2.0 Data Files](/2.0_Data_Files)**: There are two data .ris files to practice using the `revtools` package. One relates to EBSCO data from 'PsycTools', 'PsychArticles', 'MEDLINE' and 'Academic Search Complete' I used in my systematic review on workaholism literature between 1971-2024.
- **[3.0 Output Files](3.0_First_Screen_Output_Files)**: There are two .csv output files to review what the `revtools` package produces when the titles and abstracts have been screen using the Shiny app interface.

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
