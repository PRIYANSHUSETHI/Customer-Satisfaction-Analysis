
# 📊 Customer Satisfaction Analysis with Advanced Insights

This project explores and analyzes an e-commerce customer satisfaction dataset to uncover key trends, generate actionable insights, and build intelligent models for customer segmentation, satisfaction prediction, and churn detection. The project is also enriched with interactive visualizations and smart enhancements to stand out in data science portfolios.

---

## 🚀 Project Highlights

- 🔍 **Exploratory Data Analysis (EDA)** using Matplotlib, Seaborn & Plotly
- 🧮 **Summary Statistics & Demographic Insights**
- 📊 **Interactive Visualizations** for distributions and trends
- 🤖 **Customer Segmentation** using K-Means Clustering
- 🔮 **Satisfaction Prediction** using Random Forest Regression
- ⚠️ **Churn Prediction Model** based on satisfaction levels
- 💬 **Sentiment-aware NPS** using dummy review data
- 📈 **Feature Importance Analysis** for model interpretation
- 📌 **Root Cause Analysis** for low customer satisfaction

---

## 📂 Dataset

The dataset used in this analysis contains the following key columns:

- `Age`
- `Gender`
- `PurchaseAmount`
- `PurchaseFrequency`
- `ProductQualityRating`, `DeliveryTimeRating`, `CustomerServiceRating`, `WebsiteEaseOfUseRating`
- `ReturnRate`
- `DiscountUsage`
- `LoyaltyProgramMember`

---

## 🧪 Tech Stack

- **Python 3.8+**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**, **Plotly**
- **Scikit-learn** for machine learning models
- **Colab / Jupyter Notebook** for experimentation

---

## 📊 Key Visualizations

- Histograms and Box Plots for demographic and behavioral trends  
- Scatter plots for cluster segmentation  
- Feature importance bar charts  
- Violin plots for sentiment vs rating correlation  

---

## 🧠 Machine Learning Models

### 🎯 Satisfaction Score Prediction
- **Model:** Random Forest Regressor  
- **Input:** Demographics & behavior  
- **Output:** Predicted average satisfaction rating  
- **Evaluation:** R² Score, MAE

### 📉 Churn Prediction
- **Model:** Random Forest Classifier  
- **Target:** Customers with AvgRating < 2.5  
- **Evaluation:** Accuracy Score

### 👥 Customer Segmentation
- **Model:** K-Means Clustering (4 clusters)  
- **Features:** Age, Purchase behavior, Return rates

---

## 💡 Future Enhancements

- Integrate actual review data for NLP sentiment analysis
- Build a full-scale dashboard using Streamlit or Dash
- Add SHAP/LIME for model explainability
- Automate insight report generation in PDF format

---

## 📸 Screenshots

> _You can add screenshots here of your visualizations and model outputs for quick preview._

---

## 📁 Folder Structure

```
├── customer_satisfaction_analysis.py
├── E-commerce_NPA_Dataset.csv
├── README.md
```

---

## 🏁 Getting Started

1. Clone the repo  
   `git clone https://github.com/yourusername/customer-satisfaction-analysis.git`
2. Install required libraries  
   `pip install pandas matplotlib seaborn plotly scikit-learn`
3. Run the notebook/script  
   `python customer_satisfaction_analysis.py`

---
