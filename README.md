# running-performance-experimental-design
4x4 Latin Square experimental design and ANOVA analyzing footwear impact on running times.

# Footwear & Running Performance Experimental Design

A controlled \(4\times4\) Latin Square experimental study analyzing the impact of footwear types on running performance while blocking for individual runner capability and day-to-day environmental variance.

## Overview
- **Design Structure**: \(4\times4\) Latin Square (4 Runners, 4 Days, 4 Footwear Conditions)
- **Response Variable**: Time in seconds to complete two laps (800m)
- **Treatments**: Running Shoes, Sneakers, Barefoot, Flip-Flops
- **Blocking Factors**: Runner (athlete variation) and Day (fatigue and environmental conditions)

## Statistical Methodology
- **Framework**: Fixed-effects ANOVA in R
- **Pairwise Comparison**: Tukey’s Honest Significant Difference (HSD) post-hoc testing
- **Model Diagnostics**:
  - Bartlett’s test for homogeneity of variances (\(p = 0.24\))
  - Shapiro-Wilk test for normality of residuals (\(p = 0.66\))
  - Residuals vs. Fitted and Normal Q-Q diagnostic plotting

## Key Findings
- **Treatment Effect**: Identified a statistically significant 37.75-second difference between running shoes and flip-flops (Tukey HSD adjusted \(p = 0.0403\)).
- **Blocking Efficiency**: Runner blocking proved highly significant (\(p = 0.0233\)), successfully controlling for baseline athletic differences across trials.

## Deliverables
- `Footwear_and_Running_Performance_MilesReynolds.pdf`: Complete academic report and analysis writeup.
- `*.Rmd`: Reproducible R Markdown analysis pipeline.
