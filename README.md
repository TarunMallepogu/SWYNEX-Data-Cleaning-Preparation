# Retail Data Cleaning and Preparation

A data cleaning and preparation project using the UCI Online Retail dataset, completed as part of the SWYNEX Technologies Data Analyst Internship.

## Project Overview

The objective of this project was to inspect, clean, and prepare retail transaction data for reliable business analysis and reporting.

## Dataset Information

- **Dataset:** UCI Online Retail Dataset
- **Original Records:** 541,909
- **Records After Cleaning:** 536,641
- **Columns:** 8

## Data Quality Issues Identified

- Missing product descriptions
- Missing Customer IDs
- Exact duplicate records
- Data type validation requirements

## Cleaning and Preparation Performed

1. Identified and removed 5,268 exact duplicate rows.
2. Filled 1,342 missing product descriptions using the most frequent description for the matching StockCode.
3. Replaced the remaining 112 missing descriptions with `Unknown Description`.
4. Preserved missing CustomerID values rather than assigning unverified customer identities.
5. Validated the cleaned dataset and checked for remaining exact duplicates.

## Data Quality Results

| Metric | Result |
|---|---:|
| Original records | 541,909 |
| Exact duplicate rows removed | 5,268 |
| Final records | 536,641 |
| Missing descriptions after cleaning | 0 |
| Missing CustomerIDs retained | 135,037 |
| Remaining exact duplicates | 0 |

## Tools and Technologies

- Python
- Pandas
- Google Colab
- Microsoft Excel
- GitHub

## Project Files

- **Cleaned Dataset:** `SWYNEX_Cleaned_Online_Retail.xlsx`
- **Data Quality Audit Workbook:** [View Audit Workbook](https://docs.google.com/spreadsheets/d/1g4RK2SNPGpieNaLeL-ukKLqXtNDX86v7/edit?usp=sharing&ouid=101859177923478541662&rtpof=true&sd=true)

## Key Learning Outcomes

- Data quality assessment
- Missing value handling
- Duplicate detection and removal
- Data validation
- Python-based data cleaning
- Preparing datasets for further analysis

## Internship

Completed as part of the **SWYNEX Technologies Data Analyst Internship**.
