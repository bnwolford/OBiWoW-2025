# From Tidy Data to Tidy Models: Modeling Sensitive Health Data in R

Biomedical research increasingly relies on the ability to work responsibly with complex datasets while maintaining transparency and reproducibility. This hands-on workshop introduces participants to the powerful R ecosystems of tidyverse and tidymodels, with a focus on analyzing sensitive health care data. We will begin by exploring the tidyverse approach to data wrangling, visualization, and transformation—tools that make it easier to prepare real-world health data for analysis while ensuring reproducibility. Building on this foundation, we will turn to tidymodels, a cohesive framework for modeling and machine learning in R. Through guided examples, participants will learn how to manipulate data frames, clean data, specify models, create training and test splits, perform cross-validation, and evaluate predictive performance. By the end of the workshop, participants will have a practical workflow that takes them “from tidy data to tidy models,” equipping them with reproducible methods to analyze sensitive health data responsibly.

## Instructors

Brooke Wolford

## Facilitators

Gulser Caliskan Vandana Vandana

## Description

Biomedical research increasingly relies on the ability to work responsibly with complex datasets while maintaining transparency and reproducibility. This hands-on workshop introduces participants to the powerful R ecosystems of tidyverse and tidymodels, with a focus on analyzing sensitive health care data. We will begin by exploring the tidyverse approach to data wrangling, visualization, and transformation—tools that make it easier to prepare real-world health data for analysis while ensuring reproducibility. Building on this foundation, we will turn to tidymodels, a cohesive framework for modeling and machine learning in R. Through guided examples, participants will learn how to manipulate data frames, clean data, specify models, create training and test splits, perform cross-validation, and evaluate predictive performance. By the end of the workshop, participants will have a practical workflow that takes them “from tidy data to tidy models,” equipping them with reproducible methods to analyze sensitive health data responsibly.

By the end of the workshop, learners will be able to use tidyverse functions like select, filter, and mutate to manipulate a data frame. Learners will be able to perform data preprocessing for machine learning tasks, train and evaluate basic models using tidymodels, and interpret key model evaluation metrics.

## Live Troubleshooting Session

10 December 14:00 Read Rstudio.pdf

## Software Requirements

Download and install [RStudio](https://posit.co/download/rstudio-desktop/)

### Option 1 (Preferred)

in Terminal console execute the following command:

```         
git clone https://github.com/OBIWOW/OBiWoW-2025.git
```

In the bottom left panel you can navigate the file system like in a regular computer. 
Navigate to the following directory in the Files pane: 
`../OBiWoW-2025/12-Friday/from-tidy-data-to-tidy-models-modeling-sensitive-health-data-in-r/\` 
Click on `Setup.R`. This is an R script that will open in the top left panel. 
Click the source button to run the code. It will install missing packages and let you know if your environment is ready for the workshop.

### Option 2 (Simple)

in R console execute the following command:

```         
install.packages(c("ggplot2", "tidymodels", "dplyr", "tidyr", "readr","workflows","tune","mlbench","ranger","randomForest"))
```
