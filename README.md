# Data Analysis for market strategy Drinking Behaviour by Income in Finland

## Author: Min 


Market analysis for a new-market strategy, using European Social Survey data. It is a large-scale, general population survey based on face-to-face and conducted in many European countries every two years.
This report presents an analysis of drinking behavior patterns in different income groups in Finland during 2023.


## Question

How do drinking habits differ between income groups in Finland: how often people drink, whether they drink on weekdays, and how gender and life satisfaction change this?

## Data

European Social Survey, round 11 (edition 2.0), Finland respondents, 2023. The survey is a large general-population study run every two years in many Europeanå countries.

## Method

- Multinomial logit for drinking frequency by income (hypothesis 1)
- Binary logit for weekday drinking (hypothesis 2)
- K-means clustering to look for natural drinking segments

## Findings

| Hypothesis | Result |
| --- | --- |
| Higher income goes with more frequent drinking, moderated by happiness | Supported |
| Women drink less than men at the same income level | Supported |
| High-income people are more likely to drink on weekdays | Not supported |

- Weekday drinking is driven mostly by frequent drinkers, not by income.
- Middle-income respondents drink less often than the other two income groups.

Limitations: income is a household decile measure, and both drinking frequency and happiness are self-reported.

## Files

- `User Drinking Behavior Report.pdf` the full report
- `User Drinking Behaviors by Income Levels2025.qmd` the analysis code

## Tools

R (ggplot2, dplyr) and Quarto.

Author: Min Tang
