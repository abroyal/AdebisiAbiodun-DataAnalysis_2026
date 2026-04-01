This repository presents a complete analytical workflow for exploring and handling missing data within a clinical and biochemical dataset. The workflow includes identifying missing‑data patterns, evaluating whether missingness follows the MCAR (Missing Completely At Random) mechanism, performing multiple imputation using Predictive Mean Matching (PMM), comparing original and imputed distributions, and detecting outliers in the imputed dataset. All analyses are implemented in R, using widely adopted packages for data cleaning, visualization, imputation, and diagnostic assessment.

Dataset Description
File: DataSet_No_Details.csv  
Type: Mixed clinical and biochemical dataset
Observations: Human subject records
Variables include:

Hormone measurements

Lipid profile indicators

Clinical and demographic factors

Derived biochemical indices

This dataset provides a rich structure for evaluating missingness mechanisms and applying robust imputation techniques.

Key Analytical Components
1. Missing Data Exploration
Quantification of missing values

Visualization of missingness patterns

Identification of variables with high missingness

2. MCAR Testing
Application of Little’s MCAR test

Assessment of whether missingness is random or systematic

3. Multiple Imputation
Implementation of PMM using the mice package

Generation of complete datasets for downstream analysis

Density comparison of original vs. imputed values

4. Outlier Detection
IQR‑based outlier identification

Visualization of outlier direction across lipid variables

Boxplots for all numeric variables
