![Project Header](./images/monthly_ticket_trend.png)

# 🛠️ IT HelpDesk Performance Analysis & Optimization

# 📌 Project Overview

This project presents an end-to-end Exploratory Data Analysis (EDA) of a real-world IT HelpDesk ticket system.
Using 9,357 support requests, the analysis identifies operational bottlenecks, demand patterns, and SLA risk factors to support data-driven decision-making in IT operations.

The objective is to transform raw support logs into actionable business insights that can improve service efficiency, staffing allocation, and SLA compliance.

# 📊 Dataset

The dataset consists of high-volume IT HelpDesk logs containing 32 attributes, including:

Ticket creation and resolution timestamps

Incident and sub-category classifications

Agent assignment data

Multi-site location information

SLA and overdue indicators

The raw data and data dictionary are available in the Data/ directory.

# 📂 Repository Structure

Data/
│── Raw IT HelpDesk data
│── Data dictionary

notebooks/
│── 1_data_prep.ipynb
│── 2_data_summary_distributions.ipynb
│── 3_patterns_relationships.ipynb

# 🔍 Analytical Workflow

1. Data Preparation (1_data_prep.ipynb)

Data auditing and validation

Missing value handling and imputation

Datetime standardization for time-series analysis

Creation of a clean, reusable dataset

2. Statistical Profiling (2_data_summary_distributions.ipynb)

Descriptive statistics and frequency analysis

Ticket category and agent workload distribution

Outlier detection in service duration metrics

3. Patterns & Relationships (3_patterns_relationships.ipynb)

Time-series analysis of ticket volume

Identification of peak demand periods

Analysis of ticket categories most likely to breach SLAs

Visual insights for stakeholder communication

# 📈 Key Insights

Peak Demand Windows: Ticket volume spikes during specific time periods, indicating the need for adjusted staffing levels.

Primary Bottlenecks: Software-related issues account for the largest share of requests.

Efficiency Gaps: Certain site locations experience a higher concentration of overdue tickets, suggesting localized process or capacity challenges.

# 💡 Business Recommendations

Proactive Training: Develop self-service documentation for common software issues to reduce incoming ticket volume.

Resource Allocation: Rebalance IT staff coverage during identified peak periods.

SLA Monitoring: Implement automated alerts for ticket categories with higher overdue risk.

# 🛠️ Tech Stack

Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn

Tools: Jupyter Notebook, GitHub

# 🎯 Skills Demonstrated

Data cleaning and wrangling

Exploratory Data Analysis (EDA)

Data visualization and interpretation

Time-series analysis

Translating data insights into business recommendations
