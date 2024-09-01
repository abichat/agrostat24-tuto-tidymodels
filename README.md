# Creation of an end-to-end machine learning pipeline with `{tidymodels}`


Repository of the tutorial given at [AgroStat 2024 in Bragança, Portugal](http://agrostat2024.esa.ipb.pt)

> `{tidymodels}` brings together a collection of packages that facilitate the use of statistical learning methods (such as random forests, penalized linear models, etc.) within a unified and tidy framework. This tutorial will show you how to use these packages to preprocess data, build, train, and evaluate a model, optimize hyperparameters, and everything you need to know to carry out a supervised statistical learning project from start to finish.


## Pre-requisites

This workshop will be conducted in R. Familiarity with the `{tidyverse}`, especially `{dplyr}`, is recommended. To get the most out of this tutorial, please ensure that you have R version 4.1 or higher (https: //cran.r-project.org), a recent version of RStudio  (https://www.rstudio.com/download), and install the R packages we will use beforehand using the following command:

``` r
install.packages(c("tidyverse", "tidymodels", 
                   "glmnet", "ranger", "xgboost", 
                   "finetune", "workflowsets", "corrr", "vip", 
                   "ggforce", "ggrain"))
```
