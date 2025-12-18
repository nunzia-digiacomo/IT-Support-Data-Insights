## Analysis Notebooks

This folder contains the end-to-end analytical workflow for the IT HelpDesk dataset. The process is divided into three distinct phases to ensure modularity, reproducibility, and clean code standards.

## Analytical Workflow

1. Data Preparation (data_prep.ipynb)
The Foundation: This notebook focuses on transforming messy, raw IT logs into a high-quality dataset.

 - Data Auditing: Initial scan of 9,357 records to identify structural inconsistencies.

 - Cleaning & Imputation: Handled missing values in critical fields such as Item and Resolution to ensure statistical validity.

 - Type Conversion: Standardized date-time objects for Created Time and Resolved Time to enable time-series calculations.

 - Output: Generates the cleaned foundation used by all subsequent notebooks.
   

2. Statistical Profiling (data_summary_distributions.ipynb)
The "What": An exploration of individual variables and their behavior.

 - Distribution Analysis: Examining the frequency of ticket categories (e.g., Software vs. Hardware).

 - Agent Performance: Initial look at ticket distribution across the IT staff.

 - Outlier Detection: Identifying anomalies in ticket IDs and service durations.
   

3. Patterns & Relationships (patterns_relationships.ipynb)
The "Why": Advanced analysis focusing on correlations and time-based trends.

 - Time-Series Analysis: Resampling data to identify monthly and weekly volume peaks.

 - Categorical Correlations: Mapping the relationship between specific technical categories and SLA "Overdue Status."

 - Visualization: High-impact Seaborn and Matplotlib charts for business reporting.

## Environment Setup
To run these notebooks, ensure you have the following Python libraries installed:

pip install pandas numpy matplotlib seaborn
