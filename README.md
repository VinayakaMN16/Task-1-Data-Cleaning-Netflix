# Task 1: Data Cleaning & Preprocessing (Netflix Dataset)

## Objective
Clean and preprocess the raw Netflix dataset by handling missing values, duplicates, inconsistent formats, and preparing it for analysis.

## Tools Used
- Python (Pandas, NumPy, Regex)
- Jupyter Notebook

## Steps Performed
1. Removed duplicate rows (exact and by title-type-year).  
2. Handled missing values:  
   - Director, Country → "Unknown"  
   - Rating → "Not Rated"  
   - Date Added → imputed with Jan 1 of release year  
3. Standardized text fields (`type`, `rating`, `country`).  
4. Converted columns to correct datatypes (release_year → int, date_added → datetime).  
5. Parsed `duration` into numeric (`duration_int`) and unit (`duration_type`).  
6. Created new features: `added_year`, `added_month`, `primary_genre`, `primary_country`, `num_cast`.  

## Deliverables
- **Notebook with code** (`Clean_netflix_dataset.ipynb`)
- **Cleaned dataset** (`Cleaned_Netflix_dataset.csv`)  
- **Raw dataset** (`netflix_titles.csv`)   
  
## Outcome
The cleaned dataset is consistent, free from duplicates, missing values handled, and enriched with new features, making it ready for analysis and visualization.

