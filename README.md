Task 1 - Data Cleaning and Preprocessing

Dataset Used:
Netflix Movies and TV Shows Dataset (from Kaggle)

Tools Used:
- Google Colab
- Python (Pandas)

Short Summary of Changes
Removed Duplicates: Eliminated duplicate rows using drop_duplicates() to ensure data uniqueness.

Handled Missing Values:

Filled missing values in the country and rating columns with "Unknown" using fillna().

Formatted Dates:

Converted the date_added column to datetime format using pd.to_datetime() for consistency.

Standardized Text Fields:

Converted values in type and country columns to lowercase and stripped extra spaces.

Converted values in the rating column to uppercase and stripped spaces.

Renamed Columns:

Cleaned column names by converting them to lowercase and replacing spaces with underscores for uniformity and code-friendliness.
