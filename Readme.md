# Mall Customer Segmentation - Data Cleaning Project

## **Overview**
This project is part of a data analyst internship task focused on **data cleaning and preprocessing** using Python (Pandas). The dataset contains customer information such as gender, age, income, and spending score from a shopping mall.

---

## **Dataset Information**

- **Columns:**
  - `CustomerID`
  - `Gender`
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1-100)`
  
- **Source:** Kaggle - [Mall Customer Segmentation Data](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial)

---

## **Objective**

- Identify and handle missing values.
- Remove duplicate records.
- Standardize inconsistent formatting.
- Convert data types where necessary.
- Make the dataset clean, consistent, and ready for analysis or modeling.

---

## **Tools Used**
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## **Steps Performed**

1. **Loaded the data** using `pandas.read_excel()`.
2. **Checked for missing values** using `.isnull().sum()`.
3. **Identified and handled hidden missing values** like empty strings and placeholders (`"Unknown"`, `"N/A"`, etc.).
4. **Removed duplicates** using `.drop_duplicates()`.
5. **Standardized text**: capitalized and stripped whitespace from `Gender`.
6. **Converted data types**:
   - `Age`: int
   - `Annual Income`: float
   - `Spending Score`: int
7. **Renamed columns** to clean, lowercase, and consistent format using `str.lower().replace(' ', '_')`.
8. **Visualized** age distribution using a bar plot.

---

## **Data Visualization**

- **Age Distribution Bar Plot**: Shows the number of customers in each age group.
- Other visualizations can be added (e.g., income vs. spending score).

---

## **Output**

- Cleaned dataset: `cleaned_mall_customers.csv`
- Visualization: `age_distribution.png`

---

## **Conclusion**

This cleaned dataset is now ready for clustering (segmentation), dashboarding, or machine learning. It demonstrates the importance of proper data cleaning as a foundational step in any data analysis project.

---

## **Author**
- Parag 
- Data Analyst Intern
