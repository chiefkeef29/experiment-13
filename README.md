
---

## **Aim**

To perform **Exploratory Data Analysis (EDA)** on a dataset using Python and essential data analysis libraries like Pandas, NumPy, and Matplotlib in order to understand the structure, patterns, and key characteristics of the data.

---

## **Theory**

**Exploratory Data Analysis (EDA)** is a crucial step in data science that involves summarizing datasets, detecting patterns, handling missing values, and visualizing data before applying machine learning models. It helps in gaining insights and making informed decisions.

---

### **1. Data Loading and Inspection**

* **Function:** `pd.read_csv('file.csv')`

  * **Use:** Loads dataset from a CSV file into a DataFrame.

* **Function:** `df.head()`

  * **Use:** Displays the first 5 rows of the dataset to preview data.

* **Function:** `df.tail()`

  * **Use:** Displays the last 5 rows of the dataset.

* **Function:** `df.shape`

  * **Use:** Returns number of rows and columns in the dataset.

* **Function:** `df.columns`

  * **Use:** Lists all column names.

* **Function:** `df.info()`

  * **Use:** Provides summary including data types, non-null values, and memory usage.

---

### **2. Handling Missing Values**

* **Function:** `df.isnull()`

  * **Use:** Detects missing values in the dataset.

* **Function:** `df.isnull().sum()`

  * **Use:** Counts total missing values in each column.

* **Function:** `df.dropna()`

  * **Use:** Removes rows with missing values.

* **Function:** `df.fillna(value)`

  * **Use:** Replaces missing values with a specified value (mean, median, etc.).

---

### **3. Data Cleaning**

* **Function:** `df.drop(columns=['col'])`

  * **Use:** Removes unnecessary columns.

* **Function:** `df.rename(columns={'old':'new'})`

  * **Use:** Renames column names.

* **Function:** `df.duplicated()`

  * **Use:** Checks for duplicate rows.

* **Function:** `df.drop_duplicates()`

  * **Use:** Removes duplicate rows.

---

### **4. Statistical Analysis**

* **Function:** `df.describe()`

  * **Use:** Generates summary statistics (mean, median, std, min, max, quartiles).

* **Function:** `df.mean()`

  * **Use:** Calculates average of numerical columns.

* **Function:** `df.median()`

  * **Use:** Finds the middle value.

* **Function:** `df.mode()`

  * **Use:** Finds most frequently occurring values.

---

### **5. Data Visualization**

Visualization helps in understanding trends and patterns in data.

* **Function:** `plt.plot()`

  * **Use:** Creates line plots.

* **Function:** `plt.bar()`

  * **Use:** Creates bar charts.

* **Function:** `plt.hist()`

  * **Use:** Displays distribution of data.

* **Function:** `plt.scatter()`

  * **Use:** Shows relationship between two variables.

* **Function:** `plt.show()`

  * **Use:** Displays the plotted graph.

---

### **6. Correlation Analysis**

* **Function:** `df.corr()`

  * **Use:** Computes correlation between numerical variables.

* **Function:** `sns.heatmap()` *(if used)*

  * **Use:** Visualizes correlation matrix using color gradients.

---

### **7. NumPy Functions**

* **Function:** `np.array()`

  * **Use:** Creates arrays for numerical operations.

* **Function:** `np.mean()`

  * **Use:** Calculates mean of array elements.

* **Function:** `np.std()`

  * **Use:** Computes standard deviation.

---

## **Conclusion**

In this experiment, Exploratory Data Analysis was successfully performed using Python libraries. The dataset was loaded, cleaned, and analyzed to extract meaningful insights. Missing values and duplicates were handled effectively, and statistical summaries provided a deeper understanding of the data distribution.

Visualization techniques such as bar charts, histograms, and scatter plots helped in identifying trends, relationships, and anomalies. Correlation analysis further revealed dependencies between variables.

Overall, this experiment demonstrated the importance of EDA as a foundational step in data analysis, ensuring data quality and improving the effectiveness of further data modeling and decision-making processes.

---


