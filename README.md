# excel-data-visualisation
Excel analysis of 30 MLB teams using histograms, boxplots, scatterplots, descriptive statistics and linear regression to explore the relationship between ERA and wins.
## Full Project Report

[View or download my Excel analysis assignment]()

---
# Excel Data Analysis and Visualisation
## Exploring the Relationship Between Baseball Team ERA and Wins

A university project using Microsoft Excel to analyse data from 30 Major League Baseball teams. The analysis combines descriptive statistics, data visualisation, linear regression and residual checks to investigate whether earned run average (ERA) helps predict team wins.

Completed for BUS140 at Murdoch University, Semester 2, 2026, as part of Team 12.

## Project Objective

Investigate the relationship between a team's ERA and its number of wins, communicate the findings through clear visualisations, and assess the limitations of using a single variable for prediction.

ERA measures earned runs conceded per nine innings. Lower values indicate better run prevention.

## Excel Skills Demonstrated

- Using the Data Analysis ToolPak for descriptive statistics and regression.
- Creating histograms with appropriate class intervals and frequency counts.
- Producing boxplots and interpreting medians, quartiles, spread and potential outliers.
- Building scatterplots to examine relationships between numerical variables.
- Fitting and interpreting a simple linear regression model.
- Calculating and interpreting interquartile ranges and coefficients of variation.
- Reviewing residual plots and normal probability plots.
- Translating numerical outputs into a structured written report.

## Data Visualisation

The report includes seven figures, each addressing a different analytical question.

| Visualisation | What it demonstrates |
|---|---|
| ERA histogram | Distribution of team pitching performance, including concentration and skewness |
| Wins histogram | Distribution of wins and the longer tail toward lower totals |
| ERA boxplot | Median, middle 50% of observations, overall spread and potential outliers |
| Wins boxplot | Variation in team outcomes and comparison of the lower and upper tails |
| Wins versus ERA scatterplot | Direction, strength and approximate linearity of the relationship |
| Residuals versus ERA plot | Prediction errors, possible curvature and changes in error spread |
| Normal probability plot of residuals | Whether regression errors approximately follow a normal distribution |

The visualisations support the written findings and help explain patterns that summary statistics alone can miss.

## Analysis Process

1. Summarised ERA and wins using histograms, boxplots and five-number summaries.
2. Compared averages, standard deviations, variability and distribution shapes.
3. Examined the relationship using a scatterplot.
4. Estimated a least-squares regression model in Excel.
5. Interpreted the coefficients and calculated a prediction.
6. Assessed model fit and examined residuals.
7. Presented conclusions with appropriate qualifications.

## Key Findings

| Measure | Result |
|---|---|
| Number of teams | 30 |
| Average ERA | 3.8637 |
| Average wins | 81 |
| Correlation between ERA and wins | -0.7476 |
| R² | 0.5589 |
| Regression standard error | Approximately 8.26 wins |
| Predicted mean wins at ERA 4.50 | Approximately 66.54 |

### Regression Model

Predicted wins = 168.780356 − 22.719443 × ERA

Higher ERA was associated with fewer wins in the supplied dataset. A 0.10 increase in ERA corresponded to approximately 2.27 fewer predicted mean wins.

The model explained approximately 55.89% of the observed variation in wins. This is a measure of model fit, not a prediction accuracy percentage.

## Model Evaluation and Limitations

- The residual plot supported a linear model as a reasonable first approximation.
- Equal error variance and normality appeared broadly plausible, with qualifications.
- Independence could not be verified because teams play against one another.
- Miami recorded approximately 22.49 fewer wins than predicted, illustrating an unusually large prediction error.
- No marginal boxplot outliers were identified, although an unusual regression residual remained.
- The relationship describes association and does not establish causation.
- Validation using additional seasons would be needed before applying the model to future teams.

## Reviewing the Project

Open the uploaded BUS140 assignment report to review:

- All seven visualisations.
- Histogram frequency tables and descriptive statistics.
- Regression statistics and coefficient estimates.
- Predicted wins and residuals for all 30 teams.
- Interpretation, assumptions, limitations and conclusions.

The report states that its calculations and charts were produced using Excel. The original Excel workbook is a separate supporting file and is not included unless uploaded alongside the report.

## Practical Relevance

This project demonstrates how spreadsheet data can be turned into visual findings and a clearly explained analytical report.

The methods are relevant to operational reporting: understanding variation, identifying unusual results, investigating relationships and communicating uncertainty before drawing conclusions.

## Tools

- Microsoft Excel
- Excel Data Analysis ToolPak
- Microsoft Word

## Academic Context and Attribution

Author named on the submitted report: Vaibhav Saini  
Unit: BUS140  
Institution: Murdoch University  
Semester: 2, 2026

This repository presents an academic team assignment as a portfolio example. Dataset and methodological references are provided in the report.
