# Exploring and Visualizing Data

This project demonstrates basic data exploration and visualization techniques using R.  
The analysis is based on the `heights` dataset from the `dslabs` package and includes:

- Loading relevant packages and data
- Counting measurements for male and female groups
- Comparing distributions of heights using percentiles
- Exploring population sizes by continent (based on external boxplot data)
- Calculating proportions of males within certain height ranges

## Data Preparation

Make sure you have the necessary packages installed:

```r
install.packages("dslabs")
install.packages("tidyverse")
```

## Summary of Analysis
- Number of height measurements: 812 males and 238 females
- Percentiles (10th, 30th, 50th, 70th, 90th) calculated for male and female heights
- Population size exploration based on continents (Asia, Africa, Europe, Americas)
- Proportion of males with height between 69 and 72 inches: about 33.3%
