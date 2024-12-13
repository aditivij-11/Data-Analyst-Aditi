# Exploratory Data Analysis

**Project Description:**
The project focuses on understanding employee expenses versus remuneration for roles earning above $75,000 in the City of Vancouver. It analyzes the average expense per job title to inform financial planning and resource allocation.

**Project Title:**
Analyzing Expense-to-Remuneration Ratios for Optimized Budget Allocation.

**Objective:**
Identify trends and patterns in employee expenses relative to their remuneration across various job titles.

**Dataset:**
Employee remuneration and expenses dataset, with columns for job titles, remuneration, and expenses.

**Methodology:**
- Data ingestion from Amazon S3.
- Profiling data using AWS Glue Data Brew for structure and anomalies.
- Cleaning data to remove inconsistencies and errors.
- Calculating average expense per employee for each job title.

**Tools and Technologies:**
- AWS S3
- AWS Glue Data Brew
- ETL pipelines

**Deliverables:**
- A cleaned and structured dataset stored in S3.
- Analysis of average expense per job title.
- Visualizations of patterns and insights.

# Descriptive Analysis

**Project Description:**
This analysis evaluates the expense-to-remuneration ratio for roles earning above $75,000 in the City of Vancouver.

**Project Title:**
Descriptive Analysis of Employee Expenses vs. Remuneration in Vancouver.

**Objective:**
Quantify the expense-to-remuneration ratio and assess cost distributions across job titles.

**Dataset:**
Employee remuneration and expense records.

**Methodology:**
- Data ingestion and profiling.
- Cleaning and transformation using AWS Glue.
- Calculating and visualizing expense-to-remuneration ratios.

**Tools and Technologies:**
- AWS S3
- AWS Glue
- Data visualization tools

**Deliverables:**
- Expense-to-remuneration ratio metrics.
- Insights into high-spending job titles.

# Diagnostic Analysis

**Project Description:**
Examine expense patterns to pinpoint inefficiencies or irregularities in spending relative to remuneration.

**Project Title:**
Diagnostic Analysis of Employee Expense Patterns.

**Objective:**
Diagnose roles with disproportionately high expenses to optimize budget usage.

**Background:**
The City of Vancouver seeks to streamline employee spending for improved resource management.

**Dataset:**
Remuneration and expense records from AWS S3.

**Methodology:**
- Apply quality checks to datasets.
- Identify roles with the highest average expenses per employee.
- Conduct variance analysis.

**Tools and Technologies:**
- AWS S3 and Glue
- Quality control workflows in AWS Glue

**Deliverables:**
- Diagnostic report highlighting inefficiencies.
- Recommendations for expense optimization.

**Timeline:**
- Four weeks, including data profiling, analysis, and reporting.

# Data Wrangling

**Project Description:**
Prepare the dataset by resolving inconsistencies and ensuring data readiness for analysis.

**Project Title:**
Data Wrangling for Employee Remuneration and Expenses Dataset.

**Objective:**
Clean, structure, and transform raw data into a usable format for analytics.

**Background:**
Raw employee data contains anomalies that require cleaning and transformation for accurate insights.

**Dataset:**
Employee remuneration and expenses stored in Amazon S3 buckets.

**Methodology:**
- Profiling and identifying anomalies using AWS Glue Data Brew.
- Cleaning and standardizing the dataset.
- Organizing datasets into user/system folders.

**Tools and Technologies:**
- AWS S3
- AWS Glue Data Brew

**Deliverables:**
- Cleaned and transformed datasets.
- Final structured dataset stored in S3.

**Timeline:**
- Three weeks for profiling, cleaning, and structuring.

# Data Quality Control

**Project Description:**
Ensure data reliability through comprehensive quality checks and governance protocols.

**Project Title:**
Data Quality Control for Employee Expenses Dataset.

**Objective:**
Separate valid and invalid data to enhance data quality and usability.

**Background:**
Data quality is critical for accurate analysis and decision-making in budget allocation.

**Scope:**
Validate all data points in the dataset, including remuneration and expense entries.

**Methodology:**
- Apply AWS Glue pipelines for quality checks.
- Route valid and invalid data into respective folders.
- Evaluate datasets for compliance with predefined quality metrics.

**Deliverables:**
- Quality-checked datasets stored in S3.
- Summary report on data quality issues and resolutions.

**Timeline:**
Two weeks for data quality evaluation and control implementation.
