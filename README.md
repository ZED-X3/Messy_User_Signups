# Messy_User_Signups
🧹 A focused data cleaning project using Python and Pandas, covering date standardization, duplicate detection, text normalization, and missing value handling.

# Data Cleaning and Quality Validation with Pandas

![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## Overview

This project focuses on cleaning and standardizing a dataset containing common data quality issues. The goal is to transform inconsistent records into a more structured and reliable dataset using Python and Pandas.

Rather than focusing on dataset size, this project emphasizes practical data cleaning techniques, consistent formatting, and data quality validation.

## Data Cleaning Process

The cleaning workflow includes:

- **Duplicate detection:** Identifying and removing duplicate records based on user_id.

- **Date standardization:** Converting dates with different formats and separators into a consistent YYYY-MM-DD format.

- **Text normalization:** Standardizing country names and removing unnecessary whitespace.

- **Missing value handling:** Identifying missing email addresses and preserving unknown values when there is insufficient information to determine the correct values.

- **Data validation:** Checking the cleaned dataset for remaining duplicates, missing values, and formatting inconsistencies.

## Key Takeaways

This project demonstrates practical data preparation skills, including handling inconsistent date formats, standardizing categorical values, making informed decisions about missing data, and validating data quality after cleaning.

An important part of the process is distinguishing between correcting known inconsistencies and making assumptions about unknown information. Missing values are not automatically filled when doing so would require inventing data.

## Tools and Technologies

- **Python**
- **Pandas**

## Project Outcome

The result is a cleaned and standardized dataset with more consistent formatting and improved data quality, while preserving information that cannot be reliably inferred.


# Data Quality Summary

The dataset was evaluated before and after cleaning to assess the effectiveness of the cleaning process.

| Metric | Original Dataset | Cleaned Dataset |
|---|---:|---:|
| Total rows | 42 | 32 |
| Duplicate user IDs | 10 | 0 |
| Missing email addresses | 7 | 4 |
| Missing signup dates | 0 | 0 |

Date formatting and country names were standardized to improve consistency across records.

Missing email addresses were retained when the correct values could not be reliably determined.
