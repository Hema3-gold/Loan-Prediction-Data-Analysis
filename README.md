# 🏦 Loan Prediction Project

This project aims to predict whether a loan application will be approved based on applicant demographics, financial information, and credit history. It is part of my data analyst portfolio to showcase end-to-end data preparation, exploratory analysis, and machine learning modeling.

---

## 📂 Dataset

- **Source:** [Kaggle Loan Prediction Dataset](https://www.kaggle.com/)
- **Description:** Contains information on applicants, including:
  - Gender, Marital Status, Dependents, Education
  - Employment status, Applicant and Coapplicant income
  - Loan amount and term
  - Credit history
  - Property area
  - Loan approval status

---

## 🛠️ Project Workflow

1. **Data Cleaning**
   - Handling missing values with median and mode imputation.
   - Encoding categorical variables.
   - Log-transforming skewed numeric features (ApplicantIncome).

2. **Exploratory Data Analysis (EDA)**
   - Distribution plots for key variables.
   - Correlation matrix heatmap.
   - Insights on relationships among income, loan amount, and demographics.

3. **Modeling**
   - Trained Logistic Regression, Random Forest, and XGBoost classifiers.
   - Evaluated performance with Accuracy, ROC-AUC, and Confusion Matrix.
   - Compared models to identify the best-performing approach.

4. **Business Interpretation**
   - Identified credit history and applicant income as major factors influencing approval.
   - Provided recommendations for future feature engineering and model improvement.

---

## 🧠 Results

| Model               | Accuracy | AUC  |
|---------------------|----------|------|
| Logistic Regression | 0.86     | 0.80 |
| Random Forest       | 0.83     | 0.80 |
| XGBoost             | 0.83     | 0.73 |

- **Best Model:** Logistic Regression
- **Key Insights:**
  - Strong positive correlation between ApplicantIncome and LoanAmount.
  - Credit History is a critical predictor of approval.
  - Other demographic variables showed limited linear impact.

---

## 📝 Files

- `Loan_Prediction_Portfolio.ipynb`: Complete analysis notebook with code and results.
- `train.csv`: (If applicable) Raw dataset.
- `README.md`: Project documentation.

---

## 💡 Conclusion

This project demonstrates a complete workflow to predict loan approvals. Logistic Regression achieved the best balance of interpretability and performance. Future work could include hyperparameter tuning, additional feature engineering, and testing on unseen data to further improve model accuracy.

---

## 🚀 How to Run

1. Clone the repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3. Open the Jupyter Notebook:
   jupyter notebook Loan_Prediction_Portfolio.ipynb

👩‍💻 Author
Hemalatha
Aspiring Data Analyst | Rebuilding career with passion for data 📈
Completed IBM Data Analyst Certification | Learning hands-on with real projects

📬 Contact: [hemalatha210693@gmail.com]
