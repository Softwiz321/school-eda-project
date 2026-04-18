# School Dataset - Exploratory Data Analysis (EDA)

## Project Overview
This project focuses on performing Exploratory Data Analysis (EDA) on a school dataset to understand the factors influencing student performance. The analysis includes data cleaning, visualization, feature engineering, and basic predictive modeling.

---

## Objective
- Analyze real-world educational data  
- Identify relationships between school factors and student performance  
- Build a basic model to predict student scores  

---

## Data Cleaning
- Handled missing values using appropriate techniques  
- Removed duplicate records  
- Ensured consistency in data types  

---

## Exploratory Data Analysis

### 🔹 Univariate Analysis
- Distribution of Overall Student Performance (Avg_Total_Score) 
- Distribution of Schools by Location (Urban vs Rural) 
- Distribution of Schools by Infrastructure Level (Infra_Score)  
- Distribution of Teacher-Student Ratio
- 
### 🔹 Bivariate Analysis
- Impact of Infrastructure Level on Student Performance  
- Effect of Teacher Training on Student Performance  
- Comparison of Student Performance Across Top Districts  

### 🔹 Correlation Analysis
- Examined relationships between numerical features  
- Found mostly weak correlations with student performance  

---

## Key Insights
- Infrastructure shows only a slight impact on student performance  
- Teacher experience and training have minimal influence  
- Socio-economic factors (parent literacy, internet access) show weak relationships  
- Most variables have very low correlation with performance  
- Student outcomes may depend on factors not present in the dataset  

---

## Feature Engineering
- Created **Avg_Total_Score** as overall performance metric  
- Built **Infra_Score** by combining facility indicators  

---

## Predictive Modeling
- Model Used: **Random Forest Regressor**  
- Evaluation Metrics: R², MAE, RMSE  
- Result: Low predictive performance due to weak feature relationships  

---

---

## Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## Conclusion
The analysis shows that available features have limited ability to explain student performance. More detailed data is required to build a strong predictive model.

---

## Author
- Atharva Kolhe (MSC Computer Science)
