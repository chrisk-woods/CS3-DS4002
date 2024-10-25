# Tornado Analysis Results

This document presents the findings of various statistical analyses conducted on tornado data, focusing on trends over time, differences in tornado severity, and changes in injury-causing tornadoes. The analyses compare the first 5 years of data to the last 5 years, using z-tests and chi-square tests to assess significant differences.

## Proportion of Severe Tornadoes (F3 and Above)

| Period  | Total Tornadoes | Violent Tornado Count |
| ------- | --------------- | --------------------- |
| First 5 | 6609            | 262                   |
| Last 5  | 7436            | 972                   |

**Two-sided z-test results**:

- **Z-score**: 19.0299
- **P-value**: 0.0000

**Conclusion**: The proportion of tornadoes that are F3 or higher is significantly greater in the last 5 years compared to the first 5 years. The low p-value indicates that the difference is statistically significant.

## Proportion of Injury-Causing Tornadoes

| Period  | Total Tornadoes | Injury-causing Tornadoes |
| ------- | --------------- | ------------------------ |
| First 5 | 6609            | 609                      |
| Last 5  | 7436            | 402                      |

**Two-sided z-test results**:

- **Z-score**: -8.7166
- **P-value**: 0.0000

**Conclusion**: The proportion of tornadoes that caused injuries is significantly higher in the first 5 years compared to the last 5 years. The p-value of 0.0000 confirms that this difference is statistically significant.

## Tornado Counts by F-Scale

| F_SCALE | First_5_Count | Last_5_Count |
| ------- | ------------- | ------------ |
| F0      | 4094          | 15909        |
| F1      | 1657          | 8389         |
| F2      | 596           | 2547         |
| F3      | 213           | 782          |
| F4      | 44            | 171          |
| F5      | 5             | 19           |

**Chi-square Test**:

- **Chi-square statistic**: 71.616
- **Degrees of freedom**: 5
- **P-value**: 4.7215e-14

**Conclusion**: The differences in the distribution of tornado counts by F-Scale between the first and last 5 years are statistically significant, indicating a shift in the frequency of different tornado intensities over time.

## Trends in Tornado Frequency

| YEAR | First_5_Count | YEAR | Last_5_Count |
| ---- | ------------- | ---- | ------------ |
| 1998 | 1529          | 2019 | 1734         |
| 1999 | 1520          | 2020 | 1251         |
| 2000 | 1169          | 2021 | 1545         |
| 2001 | 1351          | 2022 | 1383         |
| 2002 | 1040          | 2023 | 1523         |

**Two-sided z-test for Mean Frequency**:

- **Z-score**: -1.3117
- **P-value**: 0.2260

**Conclusion**: The mean tornado frequency between the first 5 years and the last 5 years is not significantly different, as indicated by the p-value greater than 0.05.

## Summary

The analyses reveal significant changes in the nature of tornado occurrences over time. While the overall frequency of tornadoes has not shown a statistically significant difference, the proportion of severe (F3 and above) and injury-causing tornadoes has decreased significantly over the years. Additionally, there has been a significant change in the distribution of tornado intensities, as evidenced by the chi-square test results.
