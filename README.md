# Online-Payments-Fraud-Detection
This project uses machine learning to detect fraudulent transactions in online payments. It involves data preprocessing, feature engineering, model training, and evaluation. The notebook demonstrates fraud detection using classification models, helping to enhance transaction security in digital payment systems.

Key objectives:
- Preprocess and clean transaction data.
- Perform **exploratory data analysis (EDA)** to identify fraud patterns.
- Train and evaluate classification models for fraud detection.
- Compare performance using metrics like accuracy, precision, recall, and F1-score.

---

## 📊 Dataset
The dataset consists of transaction records with features like:
- **Transaction Type** (CASH-IN, CASH-OUT, TRANSFER, etc.)
- **Amount**
- **Balance details** (old and new balances for sender/receiver)
- **Fraud Label** (fraudulent or not)

---

## 🛠️ Methodology
1. **Data Cleaning & Preprocessing** – Handle missing values and irrelevant features.  
2. **Exploratory Data Analysis (EDA)** – Visualize fraud distribution and transaction behavior.  
3. **Feature Engineering** – Create meaningful features to improve detection.  
4. **Model Training** – Apply machine learning model- DecisionTreeClassifier.  

---

## 📌 Key Insights
- Fraud is highly imbalanced compared to legitimate transactions.  
- Certain transaction types (like **TRANSFER** and **CASH-OUT**) are more prone to fraud.  
- Machine learning models can achieve strong fraud detection accuracy when tuned properly.  

---

## 🛠️ Tools & Technologies
- **Python**  
- **Jupyter Notebook**  
- **Pandas, NumPy** – Data handling & preprocessing    
