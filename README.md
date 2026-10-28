# Marketing A/B Test: Ad vs PSA

Analysis of a marketing A/B test: does showing an ad increase the conversion rate
compared with a neutral public service announcement (PSA)?

## Key results
- Conversion rate: **2.55%** (ad) vs **1.79%** (control)
- Difference: **0.77 percentage points** (95% CI: 0.59 to 0.95), p < 0.001
- Relative lift: **~43%**
- Conclusion: the ad significantly increases conversion

## What I did
- Checked data quality (missing values, duplicates, group sizes)
- Verified that the groups are comparable (ads shown, day, hour; effect size with Cramér's V)
- Compared conversion rates with a two-sample test of proportions and a confidence interval
- Described limitations of the test

## Tools
R, tidyverse, ggplot2, R Markdown

## Files
- `ab_test.Rmd`: source code of the report
- `ab_test.html`: rendered report (download and open in a browser)
