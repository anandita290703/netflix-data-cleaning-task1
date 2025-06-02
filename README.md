# netflix-data-cleaning-task1
import pandas as pd

# Load the dataset
df = pd.read_csv("netflix_titles.csv")

# Show first 5 rows
print(df.head())

# Check basic info (columns, data types, non-null counts)
print("\n--- Dataset Info ---")
print(df.info())

# Count missing values in each column
print("\n--- Missing Values ---")
print(df.isnull().sum())

# Check for duplicate rows
print("\n--- Duplicate Rows ---")
print("Number of duplicates:", df.duplicated().sum())
