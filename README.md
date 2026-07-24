# 📊 Advanced Analytics & Customer Churn Prediction

An end-to-end data analytics and machine learning project using the **IBM Telco Customer Churn Dataset**. This project combines statistical analysis, customer segmentation, and predictive modeling to identify churn drivers, discover customer groups, and predict customer churn with high accuracy.

---

## 📌 Project Overview

Customer churn is one of the biggest challenges faced by subscription-based businesses. Retaining existing customers is significantly more cost-effective than acquiring new ones.

This project applies advanced analytics techniques to:

- Understand customer behavior
- Identify factors influencing churn
- Perform statistical validation
- Segment customers into meaningful groups
- Build machine learning models for churn prediction
- Generate actionable business recommendations

---

## 🎯 Project Objectives

- Perform descriptive and inferential statistical analysis
- Validate business assumptions using hypothesis testing
- Discover customer segments through clustering
- Build predictive models for churn prediction
- Compare multiple machine learning algorithms
- Generate business-driven insights and recommendations

---

# 📂 Dataset

**Dataset:** IBM Telco Customer Churn Dataset

The dataset contains customer demographic information, subscription details, billing information, service usage, and churn status.

### Dataset Size

- **Rows:** 7,043
- **Features:** 50 (before preprocessing)

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy
- Statsmodels

---

# 📈 Project Workflow

## 1️⃣ Data Preparation

- Data Cleaning
- Missing Value Handling
- Data Type Conversion
- Feature Selection
- Encoding Categorical Variables
- Feature Scaling

---

## 2️⃣ Descriptive Statistics

Performed statistical summary including:

- Mean
- Median
- Mode
- Variance
- Standard Deviation
- Skewness
- Kurtosis

### Business Outcome

Provided an overview of customer demographics, billing patterns, and service usage.

---

## 3️⃣ Correlation Analysis

Generated a correlation matrix to identify relationships among numerical variables.

### Key Findings

- Satisfaction Score showed the strongest negative relationship with churn.
- Customer Tenure positively influenced Total Revenue.
- Monthly Charges positively correlated with churn.

---

## 4️⃣ Confidence Interval

Estimated the population mean of Monthly Charges using a 95% Confidence Interval.

### Business Outcome

Provided a statistically reliable estimate of average customer billing.

---

## 5️⃣ Hypothesis Testing

Performed:

- Independent Sample T-Test
- Chi-Square Test
- One-Way ANOVA

### Business Outcome

Validated statistically significant relationships between customer characteristics and churn behavior.

---

# 👥 Customer Segmentation

Applied **K-Means Clustering** to group customers with similar characteristics.

### Techniques Used

- StandardScaler
- Elbow Method
- Silhouette Score
- PCA Visualization

### Results

Identified **4 meaningful customer segments**, including:

- High-value loyal customers
- High-risk churn customers
- Premium long-term customers
- Newly acquired customers

### Business Value

Supports personalized marketing strategies and customer retention initiatives.

---

# 🤖 Predictive Modeling

Built and compared three supervised machine learning models.

### Models

- Logistic Regression
- Decision Tree
- Random Forest

---

## 📊 Model Performance

| Model | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
|--------|---------:|----------:|--------:|---------:|--------:|
| Logistic Regression | **96.10%** | 94.43% | **90.64%** | **92.50%** | **99.27%** |
| Decision Tree | 95.17% | **98.73%** | 82.89% | 90.12% | 98.60% |
| Random Forest | 95.53% | 98.14% | 84.76% | 90.96% | 98.20% |

---

## 🏆 Best Model

**Logistic Regression**

Reason:

- Highest Accuracy
- Highest Recall
- Highest F1 Score
- Highest ROC-AUC

Making it the most suitable model for customer churn prediction.

---

# 📈 Visualizations

The project includes:

- Correlation Heatmap
- Confidence Interval Visualization
- Elbow Method
- Silhouette Score Analysis
- PCA Cluster Visualization
- Cluster Distribution
- Confusion Matrices
- ROC Curve Comparison
- Feature Importance
- Model Comparison Chart

---

# 💼 Business Insights

- Customer churn can be predicted with over **96% accuracy**.
- Customer Satisfaction is the strongest indicator of churn.
- Month-to-Month contracts experience the highest churn rates.
- Long-term customers contribute significantly more revenue and lifetime value.
- Customer segmentation enables targeted marketing and personalized retention campaigns.
- Logistic Regression provides the best balance between precision and recall for churn prediction.

---

# 💡 Business Recommendations

- Proactively identify high-risk customers using the predictive model.
- Improve customer satisfaction through better support and engagement.
- Encourage customers to switch from Month-to-Month to long-term contracts.
- Personalize marketing campaigns based on customer segments.
- Prioritize retention efforts for high-value customers to maximize Customer Lifetime Value (CLTV).

---

# 🚀 Future Improvements

- XGBoost
- LightGBM
- CatBoost
- Hyperparameter Tuning
- Cross Validation
- SHAP Explainability
- Streamlit Deployment
- Real-Time Prediction API
- Power BI Dashboard Integration

---

# 📁 Project Structure

```
advanced-analytics-customer-churn-prediction/
│
├── notebooks/
├── data/
├── images/
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

# 👨‍💻 Author

**Prayas Sharma**

B.Tech – Computer Science Engineering

Aspiring Data Scientist | Data Analyst | Machine Learning Enthusiast

---

## ⭐ If you found this project helpful, please consider giving it a star!
