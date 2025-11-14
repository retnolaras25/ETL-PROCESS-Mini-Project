# ETL-PROCESS-Mini-Project
This mini project is created by Retno to track the learning process of Python. 
This ETL process was created in Google Colab using Netflix dataset. The purpose of this process was to get a clear Netflix dataset before dive deep into analytical process. 


# 📊 Mini Project: ETL (Extract, Transform, Load) Netflix Dataset

This project focuses on cleaning, processing, and transforming the raw Netflix movies and TV shows dataset (`netflix_titles.csv`) into an analysis-ready format suitable for visualization or downstream Machine Learning models.

## 🎯 Key Objectives

1.  **Missing Data Handling:** To address and impute missing values (NaN) in critical columns like `director` and `country`.
2.  **Data Consistency:** To ensure data types and formats are consistent, especially for date and time fields.
3.  **Feature Engineering:** To extract new, useful information (such as the added month and year) from existing timestamp columns.


## ⚙️ Tools and ETL Process

The entire project was executed using **Google Colab** and the core data manipulation library, **Pandas**, in Python.

### Key Transformation Steps:

* **Handling Nulls:** Missing values in the `director` and `country` columns were imputed (filled) with the label **'Unknown'** to preserve data rows.
* **Data Type Conversion:** The date column (`date_added`) was converted into the proper *datetime* object type for chronological analysis.
* **Feature Creation:** New columns, `year_added` and `month_added`, were created by extracting components from the primary `date_added` column to facilitate trend analysis.


## ✨ Final Result

The output of this cleaning process is a new, clean, and structured dataset (`netflix_cleaned_version.csv`).
This dataset is now ready for:

1.  Visualization of content production trends over time.
2.  Modeling content popularity prediction.


