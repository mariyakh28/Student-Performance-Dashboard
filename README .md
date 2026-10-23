# Student Performance Dashboard

An interactive dashboard for exploring student academic performance, study habits, absences, and demographic information. The dashboard presents key performance indicators and visual analytics in a dark-themed interface.

## Dashboard Preview

![Student Performance Dashboard](Screenshot%202026-10-23%20213440%281%29.png)

## Overview

The dashboard summarizes student performance through headline metrics and several charts. It is designed to help users explore grade distributions and examine potential relationships between study time, absences, and final grades.

## Key Metrics

- **Highest Mark:** 96.67
- **Average Grade:** 54
- **Total Students:** 1,044
- **Lowest Mark:** 6.67

These values are the figures displayed in the supplied dashboard screenshot.

## Visualizations

### 1. Failure Count Distribution
A doughnut chart showing the distribution of students by failure count:

- 0 failures: 861 students (82.47%)
- 1 failure: 120 students (11.49%)
- 2 failures: 30 students (2.87%)
- 3 failures: a small remaining group

### 2. Grades by Study Time
A grouped bar chart comparing average grades in G1, G2, and G3 across study-time categories.

### 3. Average Absences by Address
A bar chart comparing average absences for the address categories shown as `U` and `R`.

### 4. Average Final Grade by Mother's Job
A treemap comparing average final grades across mother's job categories, including health, services, at-home, teacher, and other.

### 5. Impact of Absences on Final Grade
A scatter plot exploring the relationship between student absences and G3 (final grade), with points distinguished by sex and a trend line.

## Filters and Controls

- **School:** Filter the dashboard by school selection.
- **Sex:** Filter the dashboard by sex.
- **Reset control:** The curved-arrow control appears to provide a way to reset the dashboard selections.

> Filter behavior and reset functionality should be verified against the actual implementation.

## Insights to Explore

- Most students in the displayed distribution have zero recorded failures.
- The displayed average grade is 54, while the highest and lowest marks are 96.67 and 6.67.
- The scatter plot can help investigate whether higher absence counts tend to coincide with lower final grades.
- Differences between categories should be interpreted in context; visual associations do not by themselves establish causation.

## Data Notes

- The figures above are transcribed from the supplied screenshot.
- The screenshot does not identify the underlying dataset, data source, or calculation rules.
- Validate chart totals, percentages, and grade calculations against the source data before using the dashboard for formal reporting.
- Avoid publishing student-level or otherwise sensitive information without appropriate authorization.

## Getting Started

This README documents the dashboard shown in the screenshot. The screenshot alone does not specify the programming language, framework, dependencies, or run commands.

To complete this section for your project, add:
1. The dataset location and required columns.
2. The framework and dependency installation steps.
3. The command used to launch the dashboard.
4. Any data-cleaning or preprocessing steps.

## Suggested Technologies

If you are still choosing a stack, this kind of dashboard can be built with tools such as Python, Pandas, Plotly, and Streamlit, or with a JavaScript charting library.

## License

Add the license that applies to your project before distributing or reusing the code or data.
