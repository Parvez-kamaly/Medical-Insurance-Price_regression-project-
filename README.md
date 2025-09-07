# Medical Insurance Price Prediction

This project predicts **medical insurance costs** based on personal and lifestyle attributes such as age, sex, BMI, number of children, smoking habits, and region. It uses machine learning regression models to build predictive insights.

---

## 📂 Dataset

* **Source:** `Medical_insurance.csv` (provided in Kaggle dataset directory)
* **Features:**

  * `age`: Age of the insured person
  * `sex`: Gender (`male`, `female`)
  * `bmi`: Body Mass Index
  * `children`: Number of children/dependents covered by insurance
  * `smoker`: Smoking status (`yes`, `no`)
  * `region`: Residential area (`northeast`, `northwest`, `southeast`, `southwest`)
  * `charges`: Insurance cost (target variable)

---

## 🛠️ Project Workflow

1. **Data Loading & Inspection**

   * Load dataset with Pandas
   * Check for null/missing values

2. **Exploratory Data Analysis (EDA)**

   * Distribution of numerical features
   * Categorical feature analysis
   * Correlation heatmaps
   * Impact of smoking, age, and BMI on charges

3. **Data Preprocessing**

   * Encode categorical variables (Label Encoding & One-Hot Encoding)
   * Feature scaling with `StandardScaler`
   * Train-test split

4. **Model Training & Evaluation**
   Models implemented:

   * Linear Regression
   * Lasso Regression
   * Ridge Regression
   * Random Forest Regressor
   * Decision Tree Regressor
   * XGBoost Regressor

   **Metrics Used:**

   * MAE (Mean Absolute Error)
   * MSE (Mean Squared Error)
   * R² Score

5. **Model Comparison**

   * Performance comparison across models
   * Visualization of Train vs Test R² scores

---

## 📊 Results

* **Random Forest** performed best with:

  * Train R² ≈ 0.99
  * Test R² ≈ 0.90
* **Decision Tree** and **XGBoost** also achieved competitive performance but slightly lower generalization.

---

## 🚀 Installation & Usage

### Prerequisites

Make sure you have the following installed:

* Python 3.7+
* Jupyter Notebook or Google Colab
* Required libraries:

  ```bash
  pip install numpy pandas matplotlib seaborn scikit-learn xgboost
  ```

### Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/medical-insurance-price-prediction.git
   cd medical-insurance-price-prediction
   ```
2. Open the notebook:

   ```bash
   jupyter notebook medical-insurance-price-prediction.ipynb
   ```
3. Run all cells to reproduce results.

---

## 📈 Visualizations

* Correlation heatmap
* Distribution plots of features
* Boxplots for categorical vs numerical features
* Bar plot comparing model R² scores

---

## 🧑‍💻 Author

* **Parvez Kamaly**
  If you find this project useful, feel free to ⭐ the repo!

---

## 🔮 Future Work

* Hyperparameter tuning for better accuracy
* Deployment with Flask/Django for prediction API
* Integration with a frontend dashboard

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
