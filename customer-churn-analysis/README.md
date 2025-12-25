# Customer Churn Analysis Prediction (Machine Learning in Python)

This project performs exploratory analysis and builds classification models to predict customer churn using a real-world dataset. The goal is to demonstrate a complete ML workflow including data preprocessing, feature engineering, model training, evaluation, and interpretation, in order to identify customers who are likely to churn.
Analyzing churn helps businesses understand why customers leave and how to improve retention. High churn rates can affect revenue and business growth.

---

## 🔍 Project Overview

This machine learning project predicts whether a customer will churn based on their usage patterns, demographic information, and account details.

The workflow includes:
- Exploratory Data Analysis (EDA)
- Data cleaning and preprocessing
- Feature engineering and encoding
- Model training and comparison
- Model evaluation and insights

---

## 📁 Dataset

- **Source:** [GeeksforGeeks: Customer Churn Analysis Prediction](https://www.geeksforgeeks.org/machine-learning/python-customer-churn-analysis-prediction/)  
- **Format:** CSV  
- **Target Variable:** `Churn`
### Sample Features

| Feature | Description |
|------|-------------|
| CustomerID | Unique customer identifier |
| Gender | Male/Female |
| SeniorCitizen | Whether the customer is a senior citizen |
| Partner | Whether the customer has a partner |
| Dependents | Whether the customer has dependents |
| Tenure | Number of months the customer has stayed with the company |
| PhoneService | Whether the customer has phone service |
| MultipleLines | Whether the customer has multiple lines |
| InternetService | Type of internet service (DSL, Fiber optic, None) |
| OnlineSecurity | Whether the customer has online security |
| OnlineBackup | Whether the customer has online backup |
| DeviceProtection | Whether the customer has device protection |
| TechSupport | Whether the customer has tech support |
| StreamingTV | Whether the customer streams TV |
| StreamingMovies | Whether the customer streams movies |
| Contract | Contract type (Month-to-month, One year, Two year) |
| PaperlessBilling | Whether the customer uses paperless billing |
| PaymentMethod | Payment method used by the customer |
| MonthlyCharges | Monthly charges |
| TotalCharges | Total charges |
| Churn | **Target variable** (Yes/No) |

---

## 🛠 Tools & Technologies

- **Python**
- **Pandas, NumPy**
- **scikit-learn**
- **Matplotlib / Seaborn**
- **Jupyter Notebook**

---

## 🚀 Workflow

### 1️⃣ Exploratory Data Analysis (EDA)

- Identified numerical and categorical features
- Visualized correlations and distributions
- Analyzed churn patterns with respect to features such as contract type, tenure, and payment method
- Detected imbalances in the target variable to inform model selection and evaluation

---

### 2️⃣ Data Preprocessing & Feature Engineering

- Handled missing values and cleaned data
- Encoded categorical variables (Label Encoding / One-Hot Encoding)
- Standardized numerical features
- Created a clean, model-ready dataset

---

### 3️⃣ Model Training

Trained and compared multiple classification models:
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)
- XGBoost Classifier

---

### 4️⃣ Model Evaluation

- Evaluated models using:
  - Accuracy
  - Precision, Recall, F1-score
  - Confusion Matrix
  - ROC-AUC Score
- Compared predicted vs actual churn
- Analyzed model strengths and limitations

---

## 📊 Key Results

- Multiple classification models were trained and evaluated for predicting customer churn.
- **Random Forest and XGBoost achieved the highest predictive performance**, highlighting their effectiveness in handling feature interactions and imbalanced datasets.
- Insights from EDA and feature importance helped identify key churn drivers such as contract type, tenure, and monthly charges.

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/customer-churn-prediction.git
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3. Run the Notebook
    ```bash
    2. Install dependencies:
   ```bash
   jupyter notebook main.ipynb