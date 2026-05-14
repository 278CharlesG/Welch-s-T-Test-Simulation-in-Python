# Python Statistical Analysis & Visualization Simulation (Red Wine Quality)

This is a sample program that simulates a series of statistical methods and data visualizations using Python. It serves as an educational reference for learning data preprocessing, descriptive statistics, and hypothesis testing.

##  Project Overview
Using the "Red Wine Quality" dataset as a target, this program demonstrates how to use Python to explore the statistical relationship between chemical properties and sensory quality scores. It automates complex calculations, providing a streamlined workflow from raw data to statistical conclusions.

##  Key Features
1.  **Data Loading & Slicing**: Demonstrates how to handle CSV files with semicolon (`;`) delimiters using `pandas` and how to segment data based on specific criteria.
2.  **Descriptive Statistics**: Automatically extracts the Mean, Median, and Quartiles for specific columns.
3.  **Boxplot Analysis**: Generates boxplots to visually compare data distributions and identify shifts in the "center" of the data between groups.
4.  **Normality Check (QQ-Plot)**: Utilizes Quantile-Quantile plots to determine if the data follows a Normal Distribution, which is a prerequisite for many parametric tests.
5.  **Hypothesis Testing (Welch's T-Test)**: Simulates a Welch's T-Test to compare means between groups with unequal variances, providing a rigorous mathematical basis for the findings.
6.  **Result Verification**: Cross-validates the hypothesis testing results with quality score frequencies and boxplot summaries to ensure program accuracy.

##  Environment Dependencies
To run this program, you will need the following Python modules:pandas；matplotlib.pyplot；scipy.stats

**Installation Command:**
```bash
pip install pandas matplotlib scipy
