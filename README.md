# Task1

# Marketing Campaign Data Cleaning :

This project performs cleaning on the `marketing_campaign.csv` dataset.

## Steps Performed:
- Removed duplicates.
- Filled missing values in the `Income` column using the median.
- Standardized all column names to lowercase and replaced spaces with underscores.
- Converted `Dt_Customer` to datetime format.
- Capped outliers in the `Income` column at the 99th percentile.
- One-hot encoded categorical columns: `Education` and `Marital_Status`.
- Saved the cleaned dataset as `marketing_campaign_cleaned.csv`.




# Mall Customers Data Cleaning Script : 

 This Python script performs essential data cleaning on the Mall_Customers.csv dataset. The dataset typically contains customer information such as CustomerID, Gender, Age, Annual Income (k$), and Spending Score (1-100). Cleaning this data is a key step before using it for analysis, visualization, or machine learning tasks.

## Cleaning Process
 The script performs the following data cleaning tasks:

Load Data: Reads the raw Mall_Customers.csv using pandas.
Remove Duplicates: Ensures no repeated records exist.
Handle Missing Values: Drops rows with missing data for simplicity.
Standardize Column Names: Converts all column names to lowercase, underscores, and removes special characters for consistency.
Categorical Encoding: Converts the Gender column from string labels (Male/Female) to numerical values (0 and 1).
Outlier Handling: Applies the Interquartile Range (IQR) method to cap outliers for Age, Annual Income, and Spending Score.



# Medical Appointment Data Cleaning

This project processes and cleans a dataset of medical appointments to prepare it for analysis. The dataset includes patient demographics, appointment details, and attendance behavior.


## Cleaning Steps

1. Renamed misnamed columns for clarity (`Hipertension` → `Hypertension`, etc.)
2. Converted `ScheduledDay` and `AppointmentDay` to proper datetime objects
3. Removed invalid age entries (e.g., negative ages)
4. Converted the `No-show` column to binary format
5. Capped unusual `Handicap` values (values >1 set to 1)
6. Dropped duplicate rows
7. Reset the index



# Netflix Movies and TV Shows - Data Cleaning

This project processes the Netflix dataset to make it ready for clustering or analysis tasks.

## Cleaning Steps

1. Converted `date_added` column to datetime format
2. Replaced missing values in `director`, `cast`, `country`, and `rating` with `"Unknown"`
3. Extracted numeric values and type from the `duration` column
4. Dropped duplicate rows
5. Reset index after cleaning

## Columns Added

- `duration_int`: Numerical value extracted from the `duration` field
- `duration_type`: Type of duration (`Minutes` or `Season(s)`)


# Medical Appointment Data Cleaning

This project processes and cleans a dataset of medical appointments to prepare it for analysis. The dataset includes patient demographics, appointment details, and attendance behavior.


## Cleaning Steps

1. Renamed misnamed columns for clarity (`Hipertension` → `Hypertension`, etc.)
2. Converted `ScheduledDay` and `AppointmentDay` to proper datetime objects
3. Removed invalid age entries (e.g., negative ages)
4. Converted the `No-show` column to binary format
5. Capped unusual `Handicap` values (values >1 set to 1)
6. Dropped duplicate rows
7. Reset the index




# Contribution
Feel free to fork the project and suggest improvements — data cleaning is often project-specific, and additional validation logic or visualizations are always welcome!



