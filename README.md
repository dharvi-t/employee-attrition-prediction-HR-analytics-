#  📊 Employee-attrition-prediction-HR-analytics-

## 📝 Project Overview
Employee attrition (resignations/turnover) is a major challenge for HR departments.  
This project analyzes employee data to identify key factors affecting attrition and builds ML models to predict which employees are at high risk of leaving.  

The project includes:
- Data Cleaning & Wrangling  
- SQL Queries for HR insights  
- Exploratory Data Analysis (EDA)  
- Feature Engineering  
- Supervised Machine Learning (Logistic Regression, Decision Tree, Random Forest)  
- Unsupervised Learning (Clustering with KMeans)  
- Model Evaluation & Business Recommendations  

---

## 📂 Dataset
**IBM HR Analytics Attrition Dataset**  
- Source: [Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)  
- Rows: 1470  
- Features: Demographics, Job Role, Salary, Overtime, etc.  

---

## 🚀 Tech Stack
- Python (Pandas, NumPy, Matplotlib, Seaborn, Plotly)  
- Scikit-learn (ML Models & Evaluation)  
- SQL (SQLite in-memory database)  
- Google Colab (Notebook Environment)  

---

## 🔧 Project Workflow
1. **Data Cleaning & Wrangling**
   - Missing value handling (simulated + imputed)
   - Duplicate removal
   - Outlier detection & handling
   - Encoding categorical variables
   - Feature engineering (Tenure Buckets, Income Ratios)

2. **Exploratory Data Analysis (EDA)**
   - Attrition distribution by Department, Salary, Age
   - Correlation heatmaps
   - Interactive plots with Plotly

3. **SQL Queries**
   - Average salary per department
   - Attrition % by job role
   - Employee count by education field

4. **Machine Learning Models**
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - Model evaluation using Accuracy, Precision, Recall, F1-Score, ROC-AUC

5. **Unsupervised Learning**
   - K-Means Clustering
   - PCA for dimensionality reduction

6. **Insights & Recommendations**
   - Overtime employees are 3x more likely to leave
   - Lower-income groups show higher attrition
   - Certain departments have higher turnover risk

---

## 📈 Results
- Best model: **Random Forest** → 85% accuracy, ROC-AUC = 0.89  
- Identified key attrition drivers: Overtime, Age, MonthlyIncome, YearsAtCompany  

---

## 📑 How to Run
1. Open the notebook in **Google Colab**:  
   [👉 Click here to open Colab]()

2. Dataset will load automatically via URL (no extra setup required).  

---

## 📌 Future Work
- Add Streamlit dashboard for interactive visualization  
- Try Gradient Boosting / XGBoost for improved performance  
- Deploy model as a simple web app  

---

## 👩‍💻 Author
**Your Name**  
- [LinkedIn](https://www.linkedin.com/in/<your-profile>/)  
- [GitHub](https://github.com/<your-username>/)  

