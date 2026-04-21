# 🛡️ ChurnGuard AI: Predictive Customer Analytics

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Model-Ensemble-success?style=for-the-badge)

**ChurnGuard AI** is a machine learning solution designed to identify high-risk customers before they churn. This repository contains the complete end-to-end development pipeline—from raw data exploration to a high-performance predictive model achieving **93% accuracy**.

---

## 📊 Performance Overview
The model was developed using an **Ensemble Learning** approach, specifically optimized to balance precision and recall, ensuring that at-risk customers are identified with high reliability.

| Metric | Results |
| :--- | :--- |
| **Accuracy** | **93%** |
| **Precision** | **91%** |
| **Recall** | **89%** |
| **F1-Score** | **90%** |

---

## 🧪 The Development Pipeline
The included Jupyter Notebook (`ChurnGuard_Model.ipynb`) follows a structured Data Science workflow:

1. **Exploratory Data Analysis (EDA):** Identifying key churn drivers such as contract type, monthly charges, and support ticket frequency.
2. **Data Preprocessing:** Handling missing values, encoding categorical variables, and feature scaling for optimal model convergence.
3. **Feature Engineering:** Creating derived features to capture customer behavior patterns over time.
4. **Model Selection & Tuning:** Benchmarking multiple classifiers (Logistic Regression, Random Forest, XGBoost) and performing hyperparameter optimization.
5. **Evaluation:** Using Confusion Matrices and ROC-AUC curves to validate model robustness.

---

## 🛠️ Tech Stack & Libraries
* **Core:** Python
* **Data Manipulation:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn
* **Notebook Environment:** Jupyter / Google Colab

---

## 📂 Repository Structure
* `ChurnGuard_prediction_model.ipynb`: The primary notebook containing all code, visualizations, and model training logic.
* `synthetic_customer_behaviour_and_churn.csv`: Folder for the dataset used (if applicable).
* `requirements.txt`: List of Python libraries required to run the notebook.

---

## 💡 Key Insights
Based on the model's **Feature Importance** analysis, the top three predictors of churn identified were:
* **Contract Type:** Customers on month-to-month plans show significantly higher churn rates.
* **Tenure:** New customers are at the highest risk within the first 6 months.
* **Technical Support:** Lack of online security/tech support services correlates strongly with churn.

---

## 🚀 How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/ahmaddanyal347/Churn-Prediction-Model
2. Install dependencies:

   ```bash
    pip install -r requirements.txt
3. Run the notebook in your preferred environment to see the training process and evaluation metrics
