
# 💰 San Francisco Salaries Analysis & Prediction

This project performs **comprehensive analysis and modeling** on San Francisco employee salaries using Python, Pandas, Seaborn, and scikit-learn.

## 📂 Dataset
 
- Records: 148,654 employees  
- Columns include: BasePay, OvertimePay, OtherPay, Benefits, TotalPay, TotalPayBenefits, JobTitle, Department, Year, Agency  

## ⚙️ Project Workflow
1. **Data Loading & Cleaning**
   - Handle missing values and negative entries
   - Drop irrelevant columns (`Notes`, `Status`)  

2. **Exploratory Data Analysis (EDA)**
   - Distribution of salaries & benefits  
   - Top earners and high-paying job titles  
   - Department-wise salary comparisons  
   - Relationship between BasePay and OvertimePay  
   - Correlation heatmap & anomaly detection  

3. **Feature Engineering**
   - Encode categorical features (`JobTitle`)  
   - Create department categories based on job titles  

4. **Regression Models**
   - Linear Regression, Random Forest, XGBoost  
   - Predict **TotalPayBenefits**  

5. **Classification Models**
   - Binary classification: High vs Low income  
   - Models: Logistic Regression, Random Forest, XGBoost  

6. **Model Evaluation & Visualization**
   - Accuracy, R², MAE, RMSE  
   - Scatterplots, bar charts, line plots, and heatmaps  

## 📊 Results
- Regression:
  - Linear Regression R² ≈ 1.0  
  - Random Forest & XGBoost R² ≈ 0.997  
- Classification:
  - XGBoost Accuracy ≈ 98%  

## 🚀 Future Improvements
- Hyperparameter tuning for better performance  
- Advanced feature engineering (e.g., interaction terms)  
- Deployment via API or web app  

## 📧 Contact
For any inquiries or collaborations, feel free to reach me at: **ahmed2026shebo@gmail.com**

## 🔗 GitHub Repository
👉 [Full Notebook](https://github.com/ahmed2022Elshebawy/Machine-Learning/blob/main/San_Francisco_Salaries.ipynb)


print("README.md has been created successfully!")
