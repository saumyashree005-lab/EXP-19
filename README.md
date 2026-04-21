# NAME: SAUMYA SHREE
# PRN: 25070123161

# THEORY:

Data cleaning and statistical analysis are essential steps in data science. Data cleaning ensures that the dataset is accurate, consistent, and free from errors such as missing values and duplicates. Statistical analysis helps in understanding the data through measures like mean, median, standard deviation, and distribution patterns.
Python provides powerful libraries like pandas and numpy to perform these tasks efficiently.

# FUNCTIONS AND COMMANDS USED:
1. Importing Libraries
import pandas as pd → Used for data manipulation and analysis.
import numpy as np → Used for numerical computations.
2. Loading Dataset
pd.read_csv("file.csv") → Loads the dataset into a DataFrame.
3. Data Inspection
df.head() → Displays first 5 rows.
df.tail() → Displays last 5 rows.
df.shape → Returns number of rows and columns.
df.size → Returns total number of elements.
df.info() → Provides summary of dataset including data types and non-null values.
4. Checking Missing Values
df.isnull() → Detects missing values.
df.isnull().sum() → Counts missing values in each column.
5. Handling Missing Values
df.fillna(value) → Replaces missing values with a specific value.
df.dropna() → Removes rows containing missing values.
6. Handling Duplicate Data
df.duplicated().sum() → Counts duplicate rows.
df.drop_duplicates() → Removes duplicate entries.
7. Statistical Functions
df.describe() → Provides statistical summary (mean, std, min, max, etc.).
df.mean() → Calculates mean of numerical columns.
df.median() → Calculates median.
df.std() → Calculates standard deviation.
df.min() / df.max() → Finds minimum and maximum values.
8. Data Selection and Filtering
df['column'] → Selects a specific column.
df.loc[] → Selects rows based on conditions.
df[df['column'] > value] → Filters data based on condition.
9. Sorting Data
df.sort_values(by='column') → Sorts data in ascending order.
ascending=False → Sorts in descending order.
10. Value Analysis
df['column'].value_counts() → Counts frequency of values.
df['column'].nunique() → Counts number of unique values.
df['column'].unique() → Lists unique values.
KEY OPERATIONS PERFORMED:
Loaded and inspected dataset
Identified and handled missing values
Removed duplicate data
Performed statistical analysis (mean, median, std, etc.)
Filtered and sorted dataset
Analyzed value distribution

# CONCLUSION:
Data cleaning and statistical analysis help in improving the quality and reliability of data. Using Python libraries like pandas and numpy, we can efficiently preprocess data and extract meaningful insights. This experiment demonstrates how raw data can be cleaned and analyzed to support better decision-making.
