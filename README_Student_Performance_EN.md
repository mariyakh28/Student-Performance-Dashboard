# Student Performance Dashboard

## 1. Project Overview

This project analyzes student academic performance through an interactive dashboard featuring key performance indicators (KPIs) and visualizations. The dashboard helps explore potential relationships between students' grades, study time, absences, failure counts, and selected social and demographic characteristics.

Users can filter the results by school and sex to explore the data from different perspectives and identify general patterns in student performance.

## 2. Key Performance Indicators

The dashboard displays the following metrics:

| Metric | Value |
|---|---:|
| Highest Mark | 96.67 |
| Average Grade | 54 |
| Total Students | 1,044 |
| Lowest Mark | 6.67 |

These values are transcribed from the dashboard screenshot. The original dataset should be checked to confirm how each metric is calculated.

## 3. Visualizations and Analysis

### 3.1 Student Distribution by Failure Count

The doughnut chart shows the distribution of students by recorded failure count:

- 861 students have zero recorded failures (82.47%).
- 120 students have one recorded failure (11.49%).
- 30 students have two recorded failures (2.87%).
- Students with three failures make up a small portion of the remaining distribution.

**Finding:** Most students in the displayed distribution have no recorded failures. However, this metric alone is not enough to assess every student's current academic performance.

### 3.2 Grades by Study Time

The grouped bar chart compares average G1, G2, and G3 grades across study-time categories.

**Finding:** The chart allows users to compare performance across study-time groups and examine how grades change between the different grade measures. Determining whether more study time is associated with higher grades requires reviewing the actual values for each category and considering other factors that may influence performance.

### 3.3 Average Absences by Home Address

The bar chart displays average absences for the U and R address categories:

- **U:** Approximately 4.57 average absences.
- **R:** Approximately 4.06 average absences.

**Finding:** Category U has a slightly higher average number of absences than category R in the displayed chart. The visualization does not explain the reason for this difference, so it should not be attributed to a specific factor without further analysis.

### 3.4 Average Final Grade by Mother's Job

The treemap compares average final grades across the displayed maternal occupation categories:

| Mother's Job Category | Average Final Grade |
|---|---:|
| Health | 12.68 |
| Teacher | 12.21 |
| Services | 11.66 |
| Other | 11.02 |
| At home | 10.47 |

**Finding:** Average grades differ across the displayed categories. Health has the highest shown average, while At home has the lowest among these categories. This is a descriptive comparison and does not establish that a mother's occupation causes differences in academic achievement.

### 3.5 Relationship Between Absences and Final Grade

The scatter plot explores the relationship between the number of absences and G3 (final grade). Points are distinguished by sex, and a trend line is displayed.

**Finding:** The overall pattern suggests that higher absence counts tend to be associated with lower final grades. However, individual outcomes vary, and some students with many absences may still achieve good grades. The pattern does not prove that absences alone determine academic performance or directly cause lower grades.

## 4. Filters and Controls

The dashboard includes the following filters:

- **School:** Filters the results by school.
- **Sex:** Filters the results by sex.
- **Reset control:** The curved-arrow icon appears to provide a way to reset selections.

Filters allow users to explore differences between groups. The actual behavior of the reset control should be verified in the running dashboard.

## 5. Key Insights and Findings

Based on the figures and visualizations shown in the dashboard, the main findings are:

1. **Most students have no recorded failures:** They represent 82.47% of the displayed distribution.
2. **Student grades vary considerably:** The displayed marks range from 6.67 to 96.67, with an average grade of 54.
3. **Higher absences tend to be associated with lower final grades:** This general pattern is suggested by the scatter plot, although there are exceptions.
4. **Average absences vary slightly by address category:** Category U has a higher average than category R in the displayed chart.
5. **Average grades differ across mother's job categories:** These differences do not prove a causal relationship between a mother's occupation and a student's academic performance.
6. **Study time is worth further investigation:** Comparing G1, G2, and G3 across study-time categories can help identify performance patterns, but the underlying data must be analyzed to determine the relationship more precisely.

## 6. Conclusion

The Student Performance Dashboard provides a visual summary of academic performance, recorded failures, absences, study time, and selected social characteristics. The displayed results indicate that most students have no recorded failures, student grades vary substantially, and higher absence counts tend to coincide with lower final grades.

These findings can help identify topics for further investigation, such as the reasons for student absences and the factors associated with academic performance. However, visualizations alone cannot establish cause and effect. The original dataset should be analyzed and the findings validated before using them to inform educational decisions.

## 7. Data Notes

- The figures in this README are transcribed from the dashboard screenshot.
- The screenshot does not provide the full data source or the calculation rules for every metric.
- Verify all values and percentages against the original dataset before using them in formal reports.
- Protect student privacy and do not publish personal or sensitive information without appropriate authorization.

## 8. Technical Documentation to Add

To complete the technical documentation, consider adding:

1. The data source and names of the columns used.
2. The programming language or tool used to build the dashboard.
3. Installation steps and required dependencies.
4. Instructions for running the project and refreshing the data.
5. The applicable project and data license.

## License

Add the appropriate license before distributing the project or reusing its code and data.
