# NAME: SAUMYA SHREE
# PRN: 25070123161

# THEORY:

Data cleaning and statistical analysis are essential steps in data science. Data cleaning ensures that the dataset is accurate, consistent, and free from errors such as missing values and duplicates. Statistical analysis helps in understanding the data through measures like mean, median, standard deviation, and distribution patterns.
Python provides powerful libraries like pandas and numpy to perform these tasks efficiently.

# FUNCTIONS AND COMMANDS USED:
* Importing Libraries pd: Data handling np: Numerical operations plt: Plotting graphs sns: Advanced visualization
* Loading Dataset df = pd.read_csv("data.csv") Reads CSV file into DataFrame
* Displaying Data head() → shows first 5 rows info() → structure of dataset describe() → statistical summary
* Handling Missing Values df.isnull().sum() df.dropna() df.fillna(method='ffill') Checks and handles missing data
* Selecting Data Access specific rows and columns
* Filtering Data Filters rows based on condition
* Grouping Data Groups data and calculates mean
* Sorting Data Sorts dataset

# CONCLUSION:
Data cleaning and statistical analysis help in improving the quality and reliability of data. Using Python libraries like pandas and numpy, we can efficiently preprocess data and extract meaningful insights. This experiment demonstrates how raw data can be cleaned and analyzed to support better decision-making.
