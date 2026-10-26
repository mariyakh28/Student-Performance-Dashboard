# Student Performance Dashboard

![Student Performance Dashboard](dashboard.png)

## 1. Project Overview

This project analyzes student academic performance through an interactive Power BI dashboard featuring key performance indicators (KPIs) and visualizations. The dashboard helps explore potential relationships between students' grades, study time, absences, failure counts, and selected social and demographic characteristics.

Users can filter the results by school and sex to explore the data from different perspectives and identify general patterns in student performance.

## 2. Key Performance Indicators

| Metric | Value |
|---|---:|
| Total Students | 1,044 |
| Highest Mark | 96.67 |
| Lowest Mark | 6.67 |
| Average Grade | 54 |

## 3. Dashboard Visuals

- KPI cards: highest mark, lowest mark, average grade, total students
- Donut chart: failure count distribution
- Clustered column chart: G1, G2, and G3 by study time
- Column chart: average absences by address
- Treemap: average final grade by mother's job
- Scatter plot with trend line: impact of absences on final grade, by sex
- Slicers: filter by school and sex

## 4. Key Insights

- **Most students have no past failures:** 861 students (82.47%) had no previous failures, while 120 (11.49%) had one and 30 (2.87%) had three.
- **Absences are associated with lower final grades:** the trend line in the scatter plot slopes downward as absences increase.
- **Mother's job and final grade:** students whose mothers work in health averaged 12.68, compared with 10.47 for those whose mothers stay at home. This is an association and likely reflects other underlying factors.
- **Study time:** average grades (G1, G2, G3) rise slightly from study time group 1 to 3 and then level off, so the difference is modest.
- **Address:** students in urban areas (U) averaged 4.57 absences vs. 4.06 for rural areas (R).

## 5. Conclusion

The dashboard summarizes academic performance across 1,044 students. Most students (82.47%) have no past failures, grades range widely (6.67 to 96.67), and higher absences are associated with lower final grades.

These patterns point to areas worth acting on, such as monitoring students with high absences. Since the dashboard shows associations only, further analysis would be needed to confirm any causal effect.

## Tools

- **Power BI** (data modeling, DAX measures, visuals)
- **Power Query** (data cleaning and transformation)

## Files

- `Student_Performance.pbix`: Power BI report file
- `dashboard.png`: dashboard screenshot

## Author

**Mariya Hammash**
[LinkedIn](https://www.linkedin.com/in/mariya-hammash/) | [GitHub](https://github.com/mariyakh28)
