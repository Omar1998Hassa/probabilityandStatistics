# Glassdoor Gender Pay Gap Analysis

## Overview

This Python script analyzes gender disparities in pay across different job titles and departments using data obtained from Glassdoor. The analysis includes exploratory data analysis (EDA), visualization, statistical tests, and interpretation of results to identify potential gender biases in pay.

## Data

The dataset used for analysis is stored in the file `/kaggle/input/Glassdoor Gender Pay Gap.csv`. It contains information on job titles, gender, age, performance evaluation, education level, department, seniority, base pay, and bonus for various employees.

## Analysis Steps

1. **Exploratory Data Analysis (EDA)**: The script begins with exploratory data analysis to understand the distribution of variables and identify any patterns or anomalies in the data.

2. **Visualization**: Visualizations such as count plots and heatmaps are generated to visualize the distribution of job titles and departments by gender.

3. **Chi-Square Test for Independence**: A chi-square test for independence is conducted to determine whether there is a statistically significant relationship between job titles/departments and gender.

4. **Two-Sample Proportion Test**: For job titles/departments where the chi-square test indicates a significant relationship with gender, a two-sample proportion test is performed to further investigate the differences in proportions between male and female employees.

5. **Conclusion**: The analysis concludes with a summary of findings, including any observed gender disparities in pay and recommendations for further investigation or action.

## Usage

To replicate the analysis:

1. Ensure that you have Python installed on your machine along with necessary libraries such as NumPy, Pandas, Seaborn, and Matplotlib.
2. Download the provided Python script.
3. Update the file path in the script to point to the location of the dataset on your machine if necessary.
4. Run the script in a Python environment.
5. Review the generated visualizations and statistical test results to interpret the findings.


## Contributor

- [Omar Yasser](https://github.com/Omar1998Hassa)

## Acknowledgments

Special thanks to Glassdoor for providing the dataset used in this analysis.
