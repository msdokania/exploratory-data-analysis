# House Price Prediction (Machine Learning in Python)

This project performs exploratory analysis and builds a regression model to predict house prices using a real-world dataset. The goal is to demonstrate a complete ML workflow including data preprocessing, model training, evaluation, and interpretation, in order to  predict the price of a house based on various features such as location, size, number of bedrooms and other relevant factors.

---

## 🔍 Project Overview

This machine learning project predicts house sale prices based on various property features like location, size, number of bedrooms, etc.

The workflow includes:
- Exploratory Data Analysis (EDA)
- Data cleaning and preprocessing
- Feature engineering and encoding
- Model training and comparison
- Model evaluation and insights

---

## 📁 Dataset

- **Source:** Dataset provided in the data/ folder  
- **Format:** Excel  
- **Target Variable:** `SalePrice`
### Sample Features

| Feature | Description |
|------|-------------|
| MSSubClass | Type of dwelling |
| MSZoning | Zoning classification |
| LotArea | Lot size (sq ft) |
| LotConfig | Lot configuration |
| BldgType | Building type |
| OverallCond | Overall condition rating |
| YearBuilt | Year of construction |
| YearRemodAdd | Remodel year |
| Exterior1st | Exterior material |
| TotalBsmtSF | Basement area |
| SalePrice | **Target variable** |

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
- Visualized correlations using heatmaps
- Analyzed categorical feature distributions using bar plots to:
  - Detect dominant and rare categories
  - Identify imbalance in categorical variables
  - Inform encoding and feature-engineering decisions

These insights guided decisions such as grouping rare categories, dropping noisy features, or choosing appropriate encoding strategies.

---

### 2️⃣ Data Preprocessing & Feature Engineering

- Handled missing values
- Encoded categorical variables (One-Hot Encoding)
- Prepared numerical features for modeling
- Created a clean, model-ready dataset

### 3️⃣ Model Training

Trained and compared multiple regression models:
- Linear Regression
- Support Vector Machine (SVR)
- Random Forest Regressor

---

### 4️⃣ Model Evaluation

- Evaluated models using:
  - Mean Absolute Percentage Error (MAPE)
  - Mean Absolute Error (MAE)
  - R² Score
- Compared predicted vs actual prices
- Analyzed model strengths and limitations


---

## 📊 Key Results

- Linear Regression, Random Forest Regressor, and Support Vector Machine (SVR) were trained and evaluated using Mean Absolute Percentage Error (MAPE).
- Among the tested models, **SVR produced the lowest validation error**, suggesting stronger performance for this dataset under the chosen preprocessing and feature set.
- Results emphasize that different models perform differently depending on data characteristics and preprocessing choices.

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/msdokania/house-price-prediction.git
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3. Run the Notebook