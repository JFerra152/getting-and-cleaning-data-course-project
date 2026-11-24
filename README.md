# getting-and-cleaning-data-course-project
Repository for the JHU Getting and Cleaning Data Course Project on Coursera


## Description

`run_analysis.R` is an R script that is self-contained and will:
- Download the file from <https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip>
- Unzip it to your working directory
- Perform all of the 5 tasks described in the [project description](https://www.coursera.org/learn/data-cleaning/peer/FIZtT/getting-and-cleaning-data-course-project)
- The newly tidied dataset is called **tidydata.txt**
- Knitting the `codebook.rmd` rmarkdown, alternatively, will perform the above listed items as well as producing a codebook in HTML format for the user
- Preview of codebook: ##insert codebook when finished

## Dependencies
- `here` to build platform independent path <https://cran.r-project.org/package=here>
- `memisc` to create codebook
- `knitr` to produce html (`knitr` is installed by Rstudio by default)
- `tidyverse` for data manipulation
