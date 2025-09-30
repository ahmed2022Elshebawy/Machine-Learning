# ❤️ Heart Disease Prediction Project

This project performs **comprehensive analysis and modeling** to predict the presence of heart disease in patients using Python, Pandas, Seaborn, and scikit-learn.

## 📂 Dataset

- Records: 297 patients  
- Columns: age, sex, cp, trestbps, chol, fbs, restecg, thalach, exang, oldpeak, slope, ca, thal, target  

## ⚙️ Project Workflow

1. **Data Loading & Cleaning**
   - Handle missing values (`?`)  
   - Convert categorical features to numeric  
   - Drop rows with missing values  

2. **Exploratory Data Analysis (EDA)**
   - Histograms and boxplots for numeric features  
   - Correlation heatmap to check feature relationships  
   - Outlier detection  

3. **Feature Engineering & Selection**
   - Standardize numeric features (StandardScaler)  
   - PCA for dimensionality reduction (retain 95% variance)  
   - Recursive Feature Elimination (RFE) for key features  
   - Chi-Square test for feature importance  

4. **Train-Test Split**
   - 80% training, 20% testing  

5. **Model Training**
   - Logistic Regression, Decision Tree, Random Forest, SVM  
   - Evaluation metrics: Accuracy, Precision, Recall, F1-Score, ROC-AUC  

6. **Hyperparameter Tuning**
   - Random Forest → GridSearchCV  
   - SVM → RandomizedSearchCV  

7. **Model Evaluation & Visualization**
   - ROC curves  
   - Feature importance visualization  
   - K-Means and Hierarchical clustering  

8. **Model Saving**

9. **📊 Results**
   - Random Forest ROC-AUC ≈ 0.875
   - SVM ROC-AUC ≈ 0.874
   - Key features selected: sex, cp, trestbps, fbs, thalach, exang, slope, ca 

10. **📧 Contact**
   For any inquiries or collaborations, reach me at: ahmed2026shebo@gmail.com

## 🔗 GitHub Repository
👉 [Full Notebook]([https://github.com/ahmed2022Elshebawy/Machine-Learning/blob/main/San_Francisco_Salaries.ipynb](https://github.com/ahmed2022Elshebawy/Machine-Learning/blob/main/Heart%20Disease%20UCI.ipynb))
