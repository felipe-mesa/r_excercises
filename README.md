# R Exercises

Exercises to practice data cleaning and analysis in R with `dplyr`, `tidyr`, `readr`,
`stringr`, `lubridate` and `ggplot2`.

This is an adaptation of [guipsamora/pandas_exercises](https://github.com/guipsamora/pandas_exercises)
(BSD 3-Clause License, Copyright (c) 2018, Guilherme Samora). The questions are the same; the solutions were rewritten in R.

Each folder has two R Markdown files that you can open in RStudio:

- `Exercises.Rmd`: the questions with empty code chunks for you to fill in.
- `Solutions.Rmd`: the same questions with the solutions in R.

The data files used by the original repository are included next to the exercises.

## Install the packages

```r
install.packages(c("tidyverse", "rmarkdown", "quantmod"))
```

`quantmod` is only needed for `09_Time_Series/Getting_Financial_Data`.

## Lessons

| Topic | Exercises |
|---|---|
| 01 Getting & Knowing Your Data | Chipotle, Occupation, World Food Facts |
| 02 Filtering & Sorting | Chipotle, Euro12, Fictional Army |
| 03 Grouping | Alcohol Consumption, Occupation, Regiment |
| 04 Apply | Students Alcohol Consumption, US Crime Rates |
| 05 Merge | Auto MPG, Fictitious Names, Housing Market |
| 06 Stats | US Baby Names, Wind Stats |
| 07 Visualization | Chipotle, Online Retail, Scores, Tips, Titanic Disaster |
| 08 Creating Series and DataFrames | Pokemon |
| 09 Time Series | Apple Stock, Getting Financial Data, Investor Flow of Funds US |
| 10 Deleting | Iris, Wine |

## Notes

- World Food Facts needs the dataset downloaded from Kaggle (see Step 1 of that exercise).
- Getting Financial Data downloads stock prices from Yahoo Finance with `quantmod`, so it needs an internet connection (no API key).
- Iris and Wine read their data from the UCI Machine Learning Repository.
