
# Titanic Dataset: Task 1- Data Cleaning & Preprocessing 🚢

This project focuses on the fundamental steps of cleaning and preparing the classic Titanic dataset for machine learning analysis. The goal is to transform the raw data into a clean, structured format suitable for training predictive models.

---

 Tasks Performed

The notebook or script performs the following data preprocessing tasks:

1.  **Data Exploration**: Loaded the dataset and performed an initial analysis of its structure, data types, and summary statistics.
2.  **Handling Missing Values**:
    * Imputed missing values in the **Age** column using the median.
    * Dropped the **Cabin** column due to a high percentage of missing data.
3.  **Feature Engineering & Encoding**:
    * Dropped irrelevant columns (**Name**, **Ticket**).
    * Encoded the binary **Sex** column into numerical format (0/1).
    * Performed one-hot encoding on the multi-category **Embarked** column.
4.  **Feature Scaling**:
    * Standardized the numerical features **Age** and **Fare** using `StandardScaler` from Scikit-learn to bring them to a comparable scale.
5.  **Outlier Removal**:
    * Visualized outliers in the **Fare** column using a boxplot.
    * Removed extreme outliers based on the Interquartile Range (IQR) method.

---

 Tools & Libraries

* **Python**
* **Pandas**: For data manipulation and analysis.
* **NumPy**: For numerical operations.
* **Matplotlib & Seaborn**: For data visualization.
* **Scikit-learn**: For feature scaling (`StandardScaler`).

---

 How to Run

1.  Make sure you have all the required libraries installed.
2.  Place the `titanic.csv` dataset in the same directory as the script.
3.  Run the Python script.

The script will process the data and save the clean version.
