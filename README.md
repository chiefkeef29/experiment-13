AIM:To perform data preprocessing on a dataset by identifying and handling missing values,converting data types,

and standardizing inconsistent data entries using Python libraries like Pandas and NumPy.

Theory:
Data preprocessing is an essential step in data analysis and machine learning. Real-world datasets often

contain missing, inconsistent, or incorrectly formatted data, which can affect the accuracy of analysis.

In this experiment, various preprocessing techniques are applied:

Handling Missing Values:
Missing values (NaN) are identified using functions like isna() and handled using methods such as dropna() and fillna().
Data Type Conversion:
Columns with incorrect data types are converted into appropriate formats using functions like pd.to_numeric().
Statistical Imputation:
Missing numerical values are replaced using statistical measures such as mean and median.
Data Cleaning:
Inconsistent text data (e.g., different cases like "CSE", "cse") is standardized using string operations.
Date Formatting:
Date columns are converted into proper datetime format using pd.to_datetime() for better analysis.
These preprocessing steps improve data quality, making it suitable for further analysis and modeling.

Conclusion:
In this experiment, we successfully performed data preprocessing on a dataset by handling missing values,

converting data types, and standardizing inconsistent data. Techniques like replacing missing values with

mean/median, formatting text data, and converting date formats helped in improving the overall data quality

This preprocessing ensures that the dataset becomes clean, consistent, and ready for further data analysis

