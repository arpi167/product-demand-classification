# 🛒 Product Demand Classification System

## 📌 Project Overview
This project aims to classify products into **High Demand** and **Low Demand** categories using machine learning techniques on an online retail dataset.

---

## 🎯 Objective
To help businesses:
- Identify high-demand products
- Optimize inventory management
- Improve sales strategies

---

## 📊 Dataset
- Online Retail Dataset
- Contains transactional data including:
  - StockCode
  - Quantity
  - InvoiceDate
  - UnitPrice
  - CustomerID

---

## ⚙️ Data Preprocessing
- Removed missing values
- Removed cancelled transactions
- Removed negative quantities
- Converted date format

---

## 🔧 Feature Engineering
Created new features:
- **TotalQuantity**
- **Frequency**
- **TotalSales**

---

## 🏷️ Target Variable
- High Demand (1)
- Low Demand (0)

Based on average quantity threshold

---

## 🤖 Models Used
1. Logistic Regression  
2. Decision Tree Classifier  

---

## 📈 Results

### Logistic Regression
- Accuracy: **87.9%**

### Key Insights:
- High accuracy in predicting low-demand products
- Slightly lower recall for high-demand products

---

## 📊 Evaluation Metrics
- Accuracy Score
- Confusion Matrix
- Classification Report

---

## 🧠 Conclusion
The model successfully classifies product demand and can help businesses make data-driven decisions for inventory and marketing.

---

## 🛠️ Tools & Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- VS Code

---

## 🚀 Future Improvements
- Use advanced models (Random Forest, XGBoost)
- Add more features
- Deploy as a web application

---

## 👩‍💻 Author
Arpita Bhat
