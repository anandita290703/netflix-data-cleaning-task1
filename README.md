# Netflix Data Cleaning – Task 1 (Data Analyst Internship)

This project is a data cleaning and preprocessing task completed using the **Netflix Movies and TV Shows dataset** from Kaggle.

## 📂 Files Included
- `netflix_titles.csv` – Original dataset
- `netflix_cleaning_task1.ipynb` – Python code used for data cleaning (Google Colab)
- `netflix_titles_cleaned.csv` – Final cleaned dataset

## ✅ Summary of Data Cleaning Steps
- Removed duplicate rows
- Dropped rows with missing essential values (like `title` and `type`)
- Filled missing `director` and `cast` with `"Not Specified"`
- Filled missing `country` with `"Unknown"`
- Stripped and standardized text fields like `type` and `country`
- Converted `date_added` to datetime format
- Renamed columns to lowercase with underscores

## 🛠 Tools Used
- Python
- Pandas
- Google Colab

## 📊 Dataset Source
Kaggle: [Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)

