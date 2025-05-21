# Profiling and Data Cleaning

The <country>_eda.ipynb notebooks perform profiling and data cleaning. After that it will save the
cleaned data in data/ folder under <country>_clean.csv filename.

The process taken to profile and clean the data is the following

- Load data in to pandas DataFrame
- Use `pd.describe()` to see the basic structre of the data
- Remove columns with no meaningful values
- Identify columns with potential outliers using a box plot
- Remove outlier using z-score and save the cleaned data in data/ folder
