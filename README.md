# retail-sales-hypothesis-testing
Statistical analysis and hypothesis testing on a retail sales dataset (t-tests, ANOVA, chi-square)

## Conclusions

### 1) ANOVA – Mean Sales by Customer Segment
- **F-statistic:** 0.5874  
- **p-value:** 0.5558  
- **Decision (α = 0.05):** Fail to reject H₀  
- **Conclusion:** There is **no statistically significant difference** in mean sales across the three customer segments (Consumer, Corporate, Home Office) in this dataset.

### 2) Welch’s t-test – Mean Sales (East vs West)
- **t-statistic:** 0.9407  
- **p-value:** 0.3469  
- **Decision (α = 0.05):** Fail to reject H₀  
- **Conclusion:** There is **no statistically significant difference** in mean sales between the East and West regions.

### 3) Chi-square Test of Independence – Segment vs Region
- **χ² statistic:** 4.2075  
- **df:** 6  
- **p-value:** 0.6486  
- **Decision (α = 0.05):** Fail to reject H₀  
- **Conclusion:** Customer **Segment and Region appear independent** (no evidence of association) in this dataset.

### Overall Summary
Across all three tests at a 5% significance level, we did not find statistically significant evidence that:
- mean sales differ by segment,
- mean sales differ between East and West,
- or that segment distribution varies by region.
