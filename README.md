🏦 Loan Approval Prediction System
A machine learning project that predicts whether a loan application should be approved based on applicant details. The system is designed to assist banks and financial institutions in automating and accelerating the loan approval process using historical data.

📌 Problem Statement
Manually evaluating loan applications can be time-consuming and inconsistent. This project leverages historical data to build a predictive model that determines the likelihood of a loan being approved, improving both speed and accuracy of the process.

✅ Features
Predicts loan approval based on financial and demographic features.

Achieved 78% accuracy using Logistic Regression and Decision Tree models.

Data preprocessing includes handling missing values, encoding categorical variables, and feature scaling.

Interactive prediction interface (optional: Streamlit or CLI).

Model evaluation with confusion matrix, accuracy score, and classification report.

🧠 Algorithms Used
Logistic Regression

Decision Tree Classifier

📊 Dataset
The dataset includes features such as:

Gender

Marital Status

Education

Self Employed

ApplicantIncome

CoapplicantIncome

LoanAmount

Loan_Amount_Term

Credit_History

Property_Area

Loan_Status (Target)

Source: Kaggle Loan Prediction Dataset

⚙️ Tech Stack
Python

Pandas, NumPy

scikit-learn

Matplotlib, Seaborn

Jupyter Notebook


📈 Model Performance
Metric	Value
Accuracy	78%
Precision	~0.79
Recall	~0.75


🚀 How to Run
1.Clone the repository:
git clone https://github.com/yourusername/loan-approval-prediction.git
cd loan-approval-prediction

2.Install dependencies:

pip install -r requirements.txt

3.Run the model:
python loan_predict.py

Optionally, you can run the Jupyter Notebook (loan_approval_model.ipynb) to see step-by-step processing and model evaluation.

📌 Use Case
This project simulates how a bank might use machine learning to assist with pre-qualifying loans automatically based on historical data, reducing manual workload and improving decision consistency.
