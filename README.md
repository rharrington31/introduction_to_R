# Introduction to R

This repository contains a walkthrough of how to work with a dataset in `R`. The walkthrough covers several basic skills necessary for performing a data analysis:

* What is Data Science + the role of `R` in data science
* Base `R` vs Tidyverse
* Markdown vs. Scripts
* Overview of RStudio console
* Object assignment `<-`
* Reading in dataframes (`.csv`) - `readr`
* Basic analysis of a dataframe - `str`, `summary`, `nrow`, `ncol`, `colnames`
* Basic dataframe manipulation (`df[1:3]`, `df[1:3,]`, `df[1:3,]`, `df[1:3, 1:3]`, `df$column`, `df$column[1:3]`)
* Piping `%>%`
* Basic `dplyr` functions for data manipulation - `select`, `arrange`, `mutate`, `group_by`, `summarize`, `ungroup`
* Advanced `dplyr` functions for data manipulation - `spread`, `gather`
* Basic `ggplot2` - `geom_bar`, `geom_col`, `geom_line`, `geom_point`, `geom_histogram`, `geom_boxplot`
* For loops

The walkthrough utilizes New York City Airbnb Open Data, which can originally be found via [Kaggle](https://www.kaggle.com/dgomonov/new-york-city-airbnb-open-data/downloads/new-york-city-airbnb-open-data.zip/3).