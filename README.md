# Marathon Performance Analysis Project

## Overview
This project aims to identify key environmental predictors that influence marathon performance. Using both linear regression and random forest models, the analysis highlights factors like WBGT, air quality, and temperature as major influences on marathon outcomes.

## Method
The analysis utilized a combination of linear regression and random forest modeling to investigate the effects of environmental factors like WBGT, temperature, humidity, wind speed, and AQI on marathon performance. Data preprocessing involved reducing variables and filtering relevant data for analysis, followed by both statistical modeling and visualization to assess variable significance.

## Results
The random forest analysis identified mean AQI as the most significant predictor of marathon performance, followed by WBGT and temperature. The linear regression model also highlighted WBGT as a key factor, indicating the impact of heat stress on performance outcomes.

## Files and Structure
- **Report/`EDA_report.Rmd`**: RMarkdown containing exploratory analysis and interpretations.
- **Report/`EDA_report.pdf`**: PDF version of the exploratory analysis with code appendix.

## How to Run
Install the required R packages using `install.packages()` and run `EDA_report.Rmd` for full analysis.

## Dependencies
- `randomForest`
- `ggplot2`
- `dplyr`

## Authors
Created by Dean Zhang.
