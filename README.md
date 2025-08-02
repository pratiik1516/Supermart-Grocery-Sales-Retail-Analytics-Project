# 🛒 Supermart Grocery Sales – Retail Analytics Project

This project explores sales data from a grocery retail chain to analyze performance trends, optimize inventory decisions, and forecast future sales using regression models.

---

## 📌 Project Objective

To analyze retail sales data and build predictive models that help stakeholders understand sales drivers, seasonal trends, and category performance.

---

## 🧰 Tools & Technologies

- **Language**: Python  
- **Libraries**: pandas, numpy, matplotlib, seaborn, scikit-learn  
- **Models**: Linear Regression, Random Forest Regressor  
- **Environment**: Jupyter Notebook

---

## 📊 Dataset Overview

- **Source**: Supermart Retail Sales Data  
- **Size**: 8,500+ records  
- **Features**:
  - `Item_Identifier`, `Item_Weight`, `Item_Fat_Content`
  - `Outlet_Identifier`, `Outlet_Type`, `Outlet_Location_Type`
  - `Item_Outlet_Sales`, `Item_MRP`, `Outlet_Establishment_Year`
  - Categorical and numerical data spanning **products, stores, and sales**

---

## 🔍 Workflow

1. **Data Cleaning**  
   - Handled missing values (e.g., item weights)  
   - Standardized inconsistent categorical values  

2. **Exploratory Data Analysis (EDA)**  
   - Sales distribution across locations and outlet types  
   - Impact of product MRP and visibility on sales  
   - Seasonal and category-based performance trends  

3. **Feature Engineering**  
   - Created new variables: item categories, outlet age, etc.  
   - Label encoding for categorical variables  

4. **Model Building**  
   - Linear Regression and Random Forest Regressor  
   - Random Forest achieved **92% R²** score on test data  

5. **Model Evaluation**  
   - Evaluated with R² Score and Mean Squared Error (MSE)  
   - Visualized prediction vs. actual sales

---

## 📈 Key Outcomes

- Built a regression model with **92% accuracy** for predicting item sales  
- Identified **top-selling categories** and store types by analyzing 8,500+ transactions  
- Detected that **outlet type and item MRP** were strong predictors of sales performance

---

