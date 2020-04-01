# reactivity
This package allows you to use your own tidy datasets to automatically generate an "Introduction to Tidyverse" presentation

# Installation
To install this package, run the following in your RStudio console -  
`devtools::install_github("BAREJAA/reactivity")`

# Example
Once installed, load the package by running  
`library(reactivity)`

Then, change your working directory to the one that contains the files you will need  
`setwd(system.file("extdata", package = "reactivity"))`

Go to your working directory, open the `report.Rmd` file and click select "Knit with Paramters". Enter the name of an example dataset provided - iris.csv or heart_mod.csv. Then click the "Knit" button.

You should now have an html presentation that was built using the provided dataset

To use your own dataset, make sure that it is in a tidy format and saved as a .csv file. Move it to your working directory (the one that contains `report.Rmd`) and follow the instructions provided above but using your own dataset instead.

