# Task 1: Data Cleaning and Preprocessing

## 📁 Dataset Used
**Netflix Movies and TV Shows** (from Kaggle)

## 🛠 Tools
- Python
- Pandas
- Google Colab

## 🔧 Steps Performed
- Handled missing values using `fillna()` and `errors='coerce'` for dates
- Removed duplicate rows with `drop_duplicates()`
- Standardized text fields (e.g., `type`, `country`) using `.str.lower()` and `.str.strip()`
- Converted `date_added` to proper `datetime` format
- Renamed column headers to lowercase with underscores for consistency
- Ensured correct data types (e.g., `release_year` as integer)

## 📤 Output Files
- `DATA_CLEANING.ipynb` – Jupyter Notebook with all cleaning steps
- `netflix_cleaned.csv` – Final cleaned dataset

