# 📊 Customer Behavior Analytics & Churn Prediction Using XGBoost

This project focuses on predicting customer churn using behavioral and transactional data from an e-commerce platform. It involves a full data analysis pipeline—from data cleaning and preprocessing to model building and visualization—using Python and XGBoost.

## 🔍 Objective

To analyze customer behavior and predict churn probability using a machine learning model, enabling businesses to design targeted retention strategies and improve customer lifetime value.

---

## 🧰 Tools & Technologies

* **Languages**: Python, SQL
* **Libraries**: pandas, numpy, scikit-learn, xgboost, matplotlib, seaborn
* **Modeling**: XGBoost Classifier, GridSearchCV (for hyperparameter tuning)
* **Data Preprocessing**: Normalization, Feature Engineering, One-Hot Encoding
* **Visualization**: Matplotlib, Seaborn
* **Platform**: Google Colab

---

## 📁 Dataset

The dataset is sourced from [Kaggle](https://www.kaggle.com/datasets/ermismbatuhan/digital-marketing-ecommerce-customer-behavior), containing 20+ customer features, such as:

* `app sessions`, `desktop transactions`, `avg order value`
* `credit card info save`, `promotion clicks`, `push status`
* `location code`, `customer service calls`, etc.
* Target variable: `churn` (binary: 0 = Retained, 1 = Churned)

---

## 🧪 Project Workflow

1. **Data Cleaning**

   * Handled categorical & numerical inconsistencies
   * Replaced string-based numerical values (e.g., commas → dots)

2. **Feature Engineering**

   * Converted categorical values to numerical using `get_dummies`
   * Normalized selected features using `Normalizer()`

3. **Model Building**

   * Used `XGBoostClassifier` for churn prediction
   * Split data into train/test sets (67/33)
   * Achieved \~91.5% accuracy with default parameters

4. **Hyperparameter Tuning**

   * Used `GridSearchCV` to improve performance
   * Final model reached **92.7% accuracy** on test data

5. **Insights & Visualization**

   * Identified key churn indicators
   * Visualized churn distribution and feature importance
   * Created dashboards and plots to support stakeholder decisions

---

## 📈 Key Results

* Achieved **92.7% model accuracy** after tuning
* Enabled identification of high-risk customers
* Provided actionable insights to enhance retention strategies

---

## 🚀 How to Run

1. Clone this repo:

   ```bash
   git clone https://github.com/Gautamm188/customer-churn-xgboost.git
   cd customer-churn-xgboost
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook on [Google Colab](https://colab.research.google.com/) or locally using Jupyter.

---

## 📌 Future Improvements

* Add SHAP values for model explainability
* Deploy using Flask or Streamlit for real-time predictions
* Integrate dashboard into a BI tool like Power BI or Tableau

---

## 👨‍💻 Author

**Gautam Malhotra**
[LinkedIn](https://www.linkedin.com/in/gautam-malhotra-78a274220/) | [GitHub](https://github.com/Gautamm188)

---

Let me know if you'd like this in `README.md` format or want a demo video/GIF included!
