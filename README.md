# Task 1 – Netflix Data Cleaning and Preprocessing

## Objective

The objective of this task was to clean and preprocess the Netflix Movies and TV Shows dataset using Python and Pandas.

## Dataset

**Netflix Movies and TV Shows**

The dataset contains information about movies and TV shows available on Netflix, including title, director, cast, country, release year, rating, duration, and other details.

## Tools Used

* Google Colab
* Python
* Pandas
* NumPy
* GitHub

## Data Cleaning Performed

The following steps were performed:

1. Loaded the raw Netflix dataset using Pandas.
2. Inspected the dataset structure, columns, and data types.
3. Identified missing values using `isnull()`.
4. Handled missing text values by replacing them with "Unknown".
5. Checked for duplicate records.
6. Removed duplicate records using `drop_duplicates()`.
7. Standardized column names by converting them to lowercase and replacing spaces with underscores.
8. Standardized text values in the `type` column.
9. Converted the `date_added` column into datetime format.
10. Cleaned the `duration` column by removing unnecessary spaces.
11. Checked categorical values and data types.
12. Performed final data quality checks.
13. Saved the cleaned dataset as `cleaned_dataset.csv`.

## Repository Structure

```text
Task-1-Netflix-Data-Cleaning/
│
├── data/
│   ├── raw_dataset.csv
│   └── cleaned_dataset.csv
│
├── screenshots/
│
├── Task-1-Netflix-Data-Cleaning.ipynb
│
└── README.md
```

## Result

The Netflix dataset was cleaned by handling missing values, removing duplicates, standardizing column names and text values, converting dates, checking data types, and performing final data-quality checks.

The cleaned dataset is ready for further analysis and visualization.

## Conclusion

This task provided practical experience in identifying and resolving common data quality issues using Python and Pandas.
