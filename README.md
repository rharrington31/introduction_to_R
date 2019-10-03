# Introduction to R

This repository contains a walkthrough of how to work with a dataset in `R`. The walkthrough covers several basic skills necessary for performing a data analysis:

* What is Data Science + the role of `R` in data science
* Base `R` vs Tidyverse
* Markdown vs. Scripts
* Overview of RStudio console
* Object assignment `<-`
* Reading in dataframes (`.csv`) - `readr`
* Basic analysis of a dataframe - `dim`, `nrow`, `ncol`, `colnames`, `str`, `summary`,  `unique`
* Basic dataframe manipulation (`df[1:3]`, `df[1:3,]`, `df[1:3,]`, `df[1:3, 1:3]`, `df$column`, `df$column[1:3]`)
* For loops
* Piping `%>%`
* Basic `dplyr` functions for data manipulation - `select`, `filter`, `arrange`, `mutate`, `group_by`, `summarize`, `ungroup`
* Advanced `tidyr` functions for data manipulation - `spread`, `gather`
* Basic `ggplot2` - `geom_bar`, `geom_col`, `geom_line`, `geom_point`, `geom_histogram`, `geom_boxplot`

The walkthrough utilizes New York City Airbnb Open Data, which can originally be found via [Kaggle](https://www.kaggle.com/dgomonov/new-york-city-airbnb-open-data/). The dataset contains the following columns:

* *id* - listing ID
* *name* - name of the listing
* *host_id* - host ID
* *host_name* - name of the host
* *neighbourhood_group* - location
* *neighbourhood* - area
* *latitude* - latitude coordinates
* *longitude* - longitude coordinates
* *room_type* - listing space type
* *price* - price in dollars
* *minimum_nights* - amount of nights minimum
* *number_of_reviews* - number of reviews
* *last_review* - latest review
* *reviews_per_month* - number of reviews per month
* *calculated_host_listings_count* - amount of listing per host
* *availability_365* - number of days when listing is available for booking