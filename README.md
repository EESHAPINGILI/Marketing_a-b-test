# Marketing_a-b-test
# Project Overview

This project analyzes and compares the effectiveness of Campaign A (Ads) and Campaign B (PSA) to determine whether advertising exposure has a measurable impact on conversion rates.

## The analysis investigates:

The effect of the number of ads shown on user conversion behavior.
The best days of the week and hours of the day to run campaigns for optimal performance.
Key statistical metrics to evaluate campaign effectiveness and business impact.
# Methodology
## SQL Analysis

### SQL was extensively used to perform:

Data cleaning and exploration
Calculation of measures of central tendency (mean, median, and mode where applicable)
Conversion rate analysis
Campaign performance segmentation by day and hour
Computation of:
Absolute Lift – the direct difference in conversion rates between Ads and PSA groups.
Relative Lift – the percentage improvement in conversion rate attributable to ads.
Statistical Testing with Python

To determine whether the observed difference in conversion rates was statistically significant, a Two-Proportion Z-Test was conducted.

# Results:

### Z-Statistic: 7.3701
### P-Value: 1.705 × 10⁻¹³
# Key Findings

The extremely small p-value indicates that the difference in conversion rates between the Ads and PSA groups is statistically significant. Therefore, the observed improvement in conversions is unlikely to be due to random chance, suggesting that ad exposure has a meaningful positive impact on user conversion behavior.

# Technologies Used
### SQL – Data extraction, aggregation, and statistical calculations
### Python – Statistical hypothesis testing and validation
### Jupyter Notebook – Analysis and visualization
Conclusion

The analysis demonstrates that advertising significantly influences conversion rates. By combining SQL-based exploratory analysis with statistical hypothesis testing in Python, the project provides data-driven insights into campaign effectiveness and identifies optimal time windows for running advertising campaigns.
