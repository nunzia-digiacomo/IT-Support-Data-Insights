# Data Documentation

This folder contains the raw transactional logs used for the IT HelpDesk Analysis project.

# File Details

File Name: IT_HelpDesk_Dataset.csv
Size: 9,357 Rows x 32 Columns
Format: Comma Separated Values (.csv)

# Data Dictionary (Key Columns)
To ensure the analysis is reproducible, the following column definitions are used:

| Column Name   | Description   | Potential Insights |
| ------------- | ------------- | ------------------ |
| Request ID    | Unique ticket identifier     | Tracking total volume & duplicates     |
| Created Time  | Time of ticket submission    | Identifying peak hours/months          |
| Category      | High-level issue type        | Finding the biggest resource drains    |
| IT Agent      | Assigned staff member        | Analyzing workload distribution        |
| Resolved Time | Time of ticket closure       | Calculating Mean Time to Resolve (MTTR)|
| Overdue Status| SLA compliance flag          | Identifying efficiency bottlenecks     |
| Request Type  | Incident vs. Service Request | Understanding support vs. maintenance  |




# Data Integrity Notes
Missing Values: Handled primarily in the data_prep.ipynb notebook. Significant missing values were noted in the Item and Resolution fields.

Date Parsing: All timestamp columns follow the YYYY-MM-DD HH:MM:SS format for time-series compatibility.
