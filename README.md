# Heart Disease Data Analysis Project

This project focuses on analyzing heart disease data using various tools and techniques. The goal is to explore the data, preprocess it, and build predictive models to understand the factors contributing to heart disease. Below is an overview of the steps and tools used in this project.

## Table of Contents

1. **Python Pre-processing**
2. **Power BI**
3. **Excel**
4. **Tableau**

---

## 1. Python Pre-processing

### Data Exploration
- **Null Values Handling**: The dataset had limited null values except for the "Alcohol Consumption" column, where one value was "None," indicating never consuming alcohol. These "None" and empty values were replaced with "Never," and other rows with null values were dropped.
  
- **Numerical Description**: The `describe` function was used to provide statistical insights into the numerical features of the data. A box plot was generated to check for outliers, and none were found.

- **Encoding for the Model**: Categorical variables were encoded to prepare the data for machine learning models.

- **Heat Map**: A heat map was created to visualize the correlation between different columns in the dataset.

### Model Building
Several machine learning models were implemented to predict heart disease:
- **KNN**: Achieved an accuracy of 76.8%.
- **SVM**: Achieved an accuracy of 80.1%.
- **Tree-Based Models**:
  - **XGBOOST**: Achieved an accuracy of 80.0%.
  - **Random Forest**: Achieved an accuracy of 80.1%.

### Key Insights
- Lifestyle factors significantly impact blood pressure and the probability of developing heart disease.

---

## 2. Power BI

### Lifestyle Effects
- Power BI was used to visualize the effects of lifestyle choices on heart disease. The visualizations highlight how different lifestyle factors, such as alcohol consumption and smoking, influence the risk of heart disease.

---

## 3. Excel

### Internal Biological Levels Effects
- **Cholesterol Levels by Gender**: Analyzed the distribution of cholesterol levels (LDL and HDL) across different genders.
- **Effect of Age and Cholesterol on CRP Levels**: Explored how age and cholesterol levels impact CRP (C-reactive protein) levels.
- **Average CRP Level & BMI by Age Group**: Calculated the average CRP levels and BMI for different age groups.
- **Sugar Levels and Disease Status**: Investigated how sugar levels affect CRP levels and disease status.
- **Medical Family History and CRP Effects**: Analyzed the impact of family medical history on CRP levels and the likelihood of developing heart disease.
- **Homocysteine Levels**: Examined how high blood pressure and stress increase homocysteine levels in individuals with heart disease.

---

## 4. Tableau

### Visualizations
- **Average BMI for Age Categories**: Visualized the average BMI across different age groups.
- **Effect of Smoking on CRP Levels**: Explored how smoking affects CRP levels.
- **Chronic Diseases and Diagnosis**: Analyzed whether chronic diseases affect the diagnosis of heart disease.

---

## Conclusion

This project provides a comprehensive analysis of heart disease data using Python for preprocessing and model building, Power BI and Tableau for visualization, and Excel for additional analysis. The insights gained from this analysis can help in understanding the key factors that contribute to heart disease and in developing strategies for prevention and treatment.
