# Drinking Behaviour by Income in Finland

Market analysis for a new-market strategy, using European Social Survey data.

## Question

How do drinking habits differ between income groups in Finland: how often people drink, whether they drink on weekdays, and how gender and life satisfaction change this?

## Data Method
Data from European Social Survey, round 11 (edition 2.0), Finland respondents, 2023. The survey is a large general-population study run every two years in most European countries.

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


## Files

- `User Drinking Behavior Report.pdf` the full report
- `User Drinking Behaviors by Income Levels2025.qmd` the analysis code


Author: Kyla Tang
