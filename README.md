# Exploratory Data Analysis (EDA & Cleaning) on Iris Dataset 🌸

## 📌 Project Overview
This project performs **data cleaning, preprocessing, and exploratory data analysis (EDA)** on the Iris dataset.  
The analysis focuses on understanding the dataset structure, ensuring data quality, visualizing feature distributions, and identifying relationships between numerical variables.

---

## 📋 Project Structure
The project is organized into the following sections:
1. Introduction  
2. Data Loading  
3. Data Cleaning & Preprocessing  
4. Exploratory Data Analysis (EDA)  
5. Insights & Conclusion  

---

## 🎯 Objective
The objective of this project is to perform **data cleaning and exploratory data analysis (EDA)** on a given dataset in order to identify:
- Patterns and trends  
- Summary statistics  
- Relationships between numerical features  

---

## 🧹 Task 1: Data Cleaning and Preprocessing
### Dataset: Iris Dataset

This section demonstrates fundamental data cleaning steps using **Pandas**, including:
- Loading the dataset
- Checking for missing values
- Identifying and removing duplicate records
- Standardizing categorical variables

---

## 1️⃣ Import Libraries and Load Dataset
- Imported required libraries
- Loaded the Iris dataset into a Pandas DataFrame for analysis

---

## 2️⃣ Understand Dataset Structure
- Displayed the first few rows of the dataset
- Inspected dataset structure and data types using `.info()`

This step helped confirm column names, data types, and overall dataset size.

---

## 3️⃣ Identify Missing Values
- Checked for missing values across all columns

**Result:**  
No missing values were found; therefore, no imputation or removal was required.

---

## 4️⃣ Identify and Remove Duplicate Rows
- Checked for duplicate records
- Removed duplicate rows to ensure data integrity

---

## 5️⃣ Standardize Categorical Variables
- Standardized the `species` column by:
  - Converting all values to lowercase
  - Removing extra whitespace

This ensures consistency and prevents categorical mismatches during analysis.

---

## 6️⃣ Final Validation
- Verified dataset shape after cleaning
- Reconfirmed that no missing values remain

At this stage, the dataset was fully cleaned and ready for analysis.

---

## 🧠 Conclusion (Data Cleaning)
The dataset has been successfully cleaned and prepared.  
- No missing values were present  
- Duplicate rows were removed  
- Categorical data was standardized for consistency  

---

# 📊 Task 2: Exploratory Data Analysis (EDA)

### Description
This task focuses on exploring the dataset to identify **patterns, trends, and summary statistics** through statistical analysis and visualization.

### Objectives
- Calculate summary statistics (mean, median, mode, standard deviation)
- Visualize data distributions using histograms and boxplots
- Analyze relationships using scatter plots
- Examine correlations between numerical features

---

## 📈 Summary Statistics
Calculated:
- Mean  
- Median  
- Mode  
- Standard Deviation  

These statistics provide insight into the central tendency and variability of numerical features.

---

## 🎨 Data Visualization
Visualization libraries used:
- Matplotlib
- Seaborn  

Custom plotting parameters were applied to ensure clear and readable visuals.

---

## 🖼 Figure 1: Histograms of Numerical Features
Histograms were generated for all numerical features to examine:
- Distribution shape
- Spread
- Skewness  

**Insight:**  
This helps understand feature behavior and detect unusual distributions.

---

## 🖼 Figure 2: Boxplot of Numerical Features
Boxplots were used to:
- Observe variability
- Identify potential outliers

This visualization highlights differences in feature ranges.

---

## 🖼 Figure 3: Scatter Plot (Feature Relationship)
A scatter plot was created to analyze the relationship between:
- Sepal Length
- Petal Length  
(with species-based color encoding)

**Insight:**  
Clear clustering indicates strong feature separability among species.

---

## 🔗 Correlation Analysis
- Computed correlation matrix for numerical features
- Visualized correlations using a heatmap

---

## 🖼 Figure 4: Correlation Heatmap
The heatmap highlights:
- Strong positive correlations
- Relationships useful for future predictive modeling

---

## 🔑 Key Insights
- Petal length and petal width show a strong positive correlation
- Sepal features exhibit weaker correlations
- Species are clearly separable, making the dataset suitable for classification tasks

---

## 📌 Conclusion (EDA)
This exploratory data analysis revealed meaningful relationships and patterns within the dataset.  
The findings support **feature selection** and provide a strong foundation for future **machine learning models**.

---

## 📄 Exporting Visualizations
All EDA visualizations were exported into a **PDF report**, including:
- A cover page with project details
- Histograms
- Boxplots
- Scatter plots
- Correlation heatmap

---

## ⭐ Acknowledgements
This project was completed as part of a task from my ongoing internship at **Codveda Technologies**, where I gained hands-on experience in data analytics and machine learning through practical, real-world projects.

---

## 🔗 Author
**Alex Mathias**  
🌐 LinkedIn: https://linkedin.com/in/mathias-alex-2a1873111  
💻 GitHub: https://github.com/alexmatins234
