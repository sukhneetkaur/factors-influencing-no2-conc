# Factors Influencing NO2 Concentration in Air

This is an analytical study that seeks to explore the different factors that impact the log of nitrogen dioxide concentration in the air. Multiple regression model was used to examine the relationship between the log of no2 concentration and different explanatory variables. In addition to that, ‘all subsets regression’ was used to compare the performance of different models, after quantifying the performance using Baeysian Information Criterion (BIC) values. The reuslts of this study indicate that log of no2 concentration is positively correlated with the number of cars per hour on a particular road (p-value: &lt; 2e-16), temperature difference between 2 and 5 metres above ground in degrees Celsius (p-value: 2.52e-07), wind direction measured in degrees between 0 and 360 (p-value: 0.0417) and, increment in day number from October 1, 2001 (p-value: 0.0179) Furthermore, the log of no2 concentration in air was also found to be negatively correlated with the air temperature 2 metres above ground in degrees Celsius (p-value: 1.23e-07) and, square root of wind speed measured in meters/second (p-value: &lt; 2e-16)

## Running the code

The main code is present in the `Factors influencing NO2 conc. in air.rmd` file, and the data used for this project is stored in `NO2.csv`. The compiled report is stored in the `Factors influencing NO2 conc. in air.pdf`.

## Requirements

To run the `.rmd` file, you require the following R packages:

```
library(dplyr)
library(ggplot2)
library(gridExtra)
library(GGally)
library(readr)
library(car)
library(leaps)
```
