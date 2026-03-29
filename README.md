This repository contains an analytical workflow completed as part of the Big Data course at INRTU.
The assignment focuses on:

Understanding missing data patterns

Testing whether missingness is MCAR (Missing Completely At Random)

Performing multiple imputation using Predictive Mean Matching (PMM)

Visualizing imputed vs original distributions

Detecting outliers in the imputed dataset

The analysis is implemented entirely in R, using widely adopted packages for data cleaning, imputation, visualization, and diagnostics.

Dataset Description
The dataset used in this assignment is:

File: DataSet_No_Details.csv

Type: Mixed clinical / biochemical dataset

Rows: Human subject records

Columns:

Hormone measurements

Lipid profile variables

Clinical factors

Derived indices

Some categorical factors (later separated into factor_df)
