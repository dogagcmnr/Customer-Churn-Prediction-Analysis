# 📉 Customer Churn Prediction & Analysis

## 🎯 Project Overview  
This project focuses on analyzing customer churn patterns in a fictional telecom company using exploratory data analysis and feature engineering. The goal is to identify key factors influencing customer churn and build a solid foundation for predictive modeling.

---

## 📈 Analysis Sections

### 1. Data Loading & Initial Exploration
- Loaded customer data into Pandas DataFrame
- Assessed dataset structure, missing values, and basic statistics

### 2. Data Cleaning & Preprocessing
- Handled missing or infinite values
- Encoded categorical features using LabelEncoder
- Removed non-numeric columns for correlation analysis

### 3. Feature Engineering
- Created `avg_monthly_charges` = total charges / tenure
- Built `charges_per_service` to assess billing per active service

### 4. Univariate & Bivariate Analysis
- Visualized churn distribution across contract types, tenure, and payment methods
- Used boxplots and bar charts for variable-wise churn insight
- Created correlation heatmap of all numerical features

### 5. Business Insights & Churn Patterns
- Monthly contract customers show highest churn
- Customers without tech support or streaming services churn more
- High monthly charges correlate positively with churn

---

## 🎯 Learning Objectives
- Apply EDA best practices in a churn analysis context
- Engineer features that reflect customer behaviors
- Practice effective visualization for business storytelling
- Identify early churn indicators and customer risk profiles

---

## 📋 Key Skills Demonstrated
- **Data Preprocessing**: Handling categorical and missing data
- **Feature Engineering**: Creating insightful variables
- **Visualization**: Bar plots, boxplots, heatmaps with Matplotlib & Seaborn
- **Correlation Analysis**: Detecting patterns and associations
- **Churn Analysis**: Identifying key customer segments at risk

---

## 🚀 How to Run
1. Clone the repository and open in your IDE
2. Ensure required libraries are installed: `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`
3. Place the dataset in the same directory
4. Open `customer_churn_prediction.ipynb` in Jupyter Notebook or Colab
5. Run all cells sequentially to see the full analysis

---

## 📊 Key Findings
- Month-to-month contracts are strongly linked to high churn
- Higher charges with fewer services = higher churn risk
- Lack of tech support, streaming, or internet service increases churn
- Tenure is negatively correlated with churn — long-term users are more loyal

---

## 🔄 Next Steps
- Train a churn prediction model (Logistic Regression, XGBoost, etc.)
- Develop customer segmentation strategies
- Build an interactive churn dashboard in Tableau or Power BI
- Apply to real-world telco datasets

---

## 📧 Contact
Doğa Göçmener  
📮 gocmenerdoga@gmail.com  
🌐 [LinkedIn Profile](https://www.linkedin.com/in/dogagocmener/)  
