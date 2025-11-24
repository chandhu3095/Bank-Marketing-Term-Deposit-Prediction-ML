# 💼 Bank Marketing – Term Deposit Prediction (ML Project)

A complete end-to-end **Machine Learning project** built using the Portuguese Bank Marketing Dataset to predict whether a customer will subscribe to a **term deposit**.  
This project demonstrates full **EDA, data preprocessing, SMOTE imbalance handling, ML model comparison**, and a **production-ready model pipeline**.

---

## ✨ Features
- ⚙️ Advanced preprocessing with One-Hot Encoding & numerical scaling  
- 📉 Class imbalance handling using **SMOTE**  
- 🤖 Multiple ML Models trained & compared (**Logistic Regression, Decision Tree, Random Forest, XGBoost**)  
- 🏆 **Random Forest** selected as best model (ROC-AUC ≈ 0.90)  
- 💾 Production-ready **saved model** using Joblib  
- 📈 Visualizations: Correlation Heatmap, ROC Curve, Feature Importance  

---

## 🛠️ Tech Stack
- **Python**
- **Pandas, NumPy**
- **Scikit-Learn**
- **XGBoost**
- **Imbalanced-Learn (SMOTE)**
- **Matplotlib, Seaborn**
- **Jupyter Notebook**
- **Joblib** (model serialization)

---

## 📂 Project Structure
'''
Bank-Marketing-Term-Deposit-Prediction-ML/
│
├── notebook/
│ └── bank_marketing_analysis.ipynb # Full EDA + ML pipeline
│
├── data/
│ └── bank-additional-full.csv # Dataset (optional)
│
├── models/
│ └── random_forest_model.pkl # Saved ML model
│
├── images/
│ ├── correlation_heatmap.png
│ ├── roc_curve.png
│ └── feature_importance.png
│
├── requirements.txt # Dependencies
└── README.md # Documentation
'''
---

## 🔍 Project Workflow

### **1️⃣ Data Understanding & Cleaning**
- 41,188 records from marketing campaigns  
- Dropped leakage-prone `duration`  
- Cleaned missing values & standardized numeric columns  
- Encoded all categorical variables  

### **2️⃣ EDA Highlights**
- Distribution of age, job, and education  
- Subscription imbalance visualization  
- Month-wise conversion patterns  
- Correlation heatmap  

### **3️⃣ Feature Engineering**
- One-Hot Encoding for categorical variables  
- Standard scaling for numeric variables  
- Stratified Train-Test split  

### **4️⃣ Handling Class Imbalance**
- Applied **SMOTE** to balance minority class  
- Improved recall for subscription class  

### **5️⃣ Model Building**
Trained models:
- Logistic Regression  
- Decision Tree  
- Random Forest  
- XGBoost (if installed)  

### **6️⃣ Evaluation Metrics**
- Accuracy  
- Precision  
- Recall  
- F1-Score  
- **ROC-AUC**  
- Confusion Matrix  

### **7️⃣ Final Model Selection**
**Random Forest Classifier**  
- ROC-AUC ≈ **0.90**  
- Best performance + stability  
- Saved as a pipeline for production  

---

## 🚀 Running the Project Locally
```bash
# 1️⃣ Clone repository
git clone https://github.com/<yourusername>/Bank-Marketing-Term-Deposit-Prediction-ML.git

# 2️⃣ Enter project
cd Bank-Marketing-Term-Deposit-Prediction-ML

# 3️⃣ Install dependencies
pip install -r requirements.txt

# 4️⃣ Start Jupyter Notebook
jupyter notebook

