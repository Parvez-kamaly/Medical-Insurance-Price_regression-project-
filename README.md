# 🩺 Medical Insurance Price Prediction

This project predicts **medical insurance charges** using machine learning. It analyzes how features like **age, gender, BMI, children, smoking habits, and region** affect insurance cost, and applies regression models to estimate charges.

---

## 📂 Dataset
- **Source**: [Kaggle - Medical Cost Personal Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)  
- **Features**:
  - `age`: Age of the insured  
  - `sex`: Male / Female  
  - `bmi`: Body Mass Index  
  - `children`: Number of dependents  
  - `smoker`: Smoking status  
  - `region`: Residential area in the US  
  - `charges`: Insurance cost (target variable)  

---

## 🔎 Exploratory Data Analysis (EDA)
- Distribution of charges  
- Age vs charges  
- BMI vs charges  
- Effect of children, sex, smoker status, and region on charges  
- Correlation heatmap  

---

## ⚙️ Machine Learning Models
- **Linear Regression**  
- **Random Forest Regressor**  
- **Gradient Boosting Regressor**  
- **GridSearchCV** for hyperparameter tuning  

Models were evaluated using **R² Score, MAE, and RMSE**.

---

## 📊 Results
- Linear Regression: R² ≈ …  
- Random Forest: R² ≈ …  
- Gradient Boosting: R² ≈ …  

*(Replace with your actual notebook results)*

---

## 🚀 How to Run
```bash
# Clone the repository
git clone https://github.com/Parvez-kamaly/medical-insurance-prediction.git
cd medical-insurance-prediction

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook medical-insurance-price-prediction.ipynb

