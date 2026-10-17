# CS4048 Data Science Assignment 2

This repository contains the cleaned datasets prepared for CS4048 Data Science Assignment 2.

## Dataset A — Netflix Movies and TV Shows

- **Source:** [Kaggle — Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **Original size:** 8,807 rows × 12 columns
- **File:** `23L_0716_A2_netflix_cleaned.csv`

**Cleaning:** Corrected three duration-like rating entries, parsed `date_added`, created separate numeric variables for movie duration and TV-show seasons, and derived country and genre counts. Missing values and potential outliers were retained where appropriate.

## Dataset B — Supermarket Sales

- **Source:** Instructor-provided `supermarket_Sales.csv`
- **Original size:** 1,000 rows × 17 columns
- **File:** `23L_0716_A2_supermarket_cleaned.csv`

**Cleaning:** Converted `Date` to datetime, derived time-related variables, checked duplicates and categorical consistency, verified financial calculations, and retained potential outliers that were not confirmed errors.

## Version Information

Both cleaned datasets are published as **v1.0.0**, dated 17 October 2026, for assignment use.

