# Titanic Survival Analysis: Data Preprocessing & EDA 🚢
This project performs a complete data analysis workflow on the classic Titanic dataset. The project is divided into two main parts:

Data Cleaning & Preprocessing: Transforming the raw data into a clean, machine-learning-ready format.

Exploratory Data Analysis (EDA): Uncovering patterns, trends, and key insights from the cleaned data through visualization.

## Project Workflow
### Task 1: Data Cleaning & Preprocessing
The initial raw data was processed to create a clean and structured dataset (titanic_cleaned.csv). The key steps included:

Handling Missing Values: Imputed 'Age' with the median and dropped the 'Cabin' column.

Feature Engineering & Encoding: Converted categorical columns ('Sex', 'Embarked') into numerical formats using mapping and one-hot encoding. Dropped irrelevant columns ('Name', 'Ticket').

Feature Scaling: Standardized 'Age' and 'Fare' to ensure they are on a comparable scale.

Outlier Removal: Identified and removed extreme outliers from the 'Fare' column using the IQR method.

### Task 2: Exploratory Data Analysis (EDA)
Using the cleaned data, an exploratory analysis was conducted to understand the factors influencing passenger survival.

Summary Statistics: Generated descriptive statistics to get a numerical overview.

Distribution Analysis: Created histograms and boxplots to visualize the distribution of numerical features like 'Age' and 'Fare'.

Correlation Analysis: A heatmap was generated to visualize the correlation between different features.

Pattern Identification: Created targeted visualizations to analyze the relationship between key features and the survival outcome.

## Key Insights from EDA
The analysis revealed several strong factors influencing survival on the Titanic:

Gender: Being female was the strongest predictor of survival. Female passengers had a survival rate of over 70%, while males had a rate below 20%.

Passenger Class (Pclass): There was a clear class-based hierarchy in survival. First-class passengers had a significantly higher survival rate than third-class passengers.

Fare: Higher fares correlated positively with survival, reinforcing the 'Passenger Class' insight.

## Tools & Libraries
Python

Pandas: For data manipulation and analysis.

NumPy: For numerical operations.

Matplotlib & Seaborn: For data visualization.

Scikit-learn: For feature scaling.

## How to Run
Ensure all required libraries are installed.

Place the raw titanic.csv dataset in the project directory.

Execute the Python script. The script will first perform the cleaning steps from Task 1 and then generate the EDA plots and insights from Task 2.
The script will process the data and save the clean version.
