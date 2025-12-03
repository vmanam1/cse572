# 📊 Customer Churn Prediction using Data Mining Techniques  
### CSE 572 — Data Mining Group Project  

This repository contains the implementation and documentation for our CSE 572 Data Mining group project.  
The goal of this project is to build a complete end-to-end machine learning pipeline for **customer churn prediction** using demographic, behavioral, financial, support-related, and contract-level features.

---

## 🚀 Project Overview
Customer churn is a critical challenge for subscription-based businesses. Predicting which customers are likely to leave helps organizations reduce revenue loss, improve retention strategies, and make informed business decisions.

In this project, we:
- preprocess customer datasets,  
- perform exploratory data analysis (EDA),  
- engineer domain-specific features,  
- train multiple machine learning models,  
- evaluate their performance using multiple metrics, and  
- identify the best churn prediction pipeline.

---

## 📁 Repository Structure
```
cse572/
│
├── checkpoint1.ipynb # Project Checkpoint 1
├── checkpoint2.ipynb # Project Checkpoint 2 (general models)
├── checkpoint2_svm.ipynb # SVM experiments
├── datasetProcessing.ipynb # Data preprocessing & feature engineering
├── report/ # Final project report
├── README.md # Project documentation
└── requirements.txt # Python dependencies
```
---

## 🔧 Methods and Techniques

### **Data Preprocessing**
- Handling missing values  
- Removing irrelevant identifiers  
- Encoding categorical variables  
- Scaling numerical features  
- Train–test split

### **Feature Engineering**
- Contract-type indicators  
- Support call intensity  
- Financial reliability features (payment delays)  
- Tenure-based behavioral metrics  

### **Models Implemented**
- Logistic Regression  
- Decision Trees  
- Random Forest  
- SVM (Linear & RBF)  
- XGBoost  
- LightGBM  
- CatBoost  
- Multi-Layer Perceptron (MLP)

### **Evaluation Metrics**
- Accuracy  
- Precision  
- Recall  
- F1-score  
- ROC-AUC  

---

## 📈 Results Summary
Our experiments show that **ensemble gradient boosting models (XGBoost, LightGBM, CatBoost)** and the **MLP** consistently outperform classical models, achieving:

> **✔ Over 98% accuracy and F1-score across datasets**

The models generalize well to external datasets such as the **IBM Telco Customer Churn Dataset** and **Kaggle Customer Churn Dataset**.

---

## 👥 Team Members
- Vishal Manam  
- Madhuri Chandanala

---

## 🏗️ How to Run the Project

### 1. Clone the repository
```bash
git clone https://github.com/vmanam1/cse572.git
cd cse572
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Launch the notebooks
```bash
jupyter notebook
```

## 📚 References

This project uses techniques and datasets referenced in our final report, including:

- **Gradient Boosting** (Friedman, 2001)  
- **XGBoost**, **LightGBM**, **CatBoost**  
- **Telecom & Kaggle Customer Churn Datasets**  
- **Classic churn prediction research literature**  

---

## 📜 License

This repository is created for academic purposes as part of  
**Arizona State University — CSE 572: Data Mining**.
