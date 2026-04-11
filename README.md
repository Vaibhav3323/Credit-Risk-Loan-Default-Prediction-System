# 💳 Credit Risk - Loan Default Prediction System
[App Screenshot](Screenshot 2026-03-26 023819)

## 🎯 Project Overview
A complete End-to-End Machine Learning project that predicts 
whether a loan applicant will default or not using real-world 
financial data.

## 🚀 Live Demo
> App deployed using Streamlit
> [Click here to see live modle](https://lore-unrefusing-london.ngrok-free.dev/)

## 📊 Dataset
- Source: Kaggle Loan Dataset
- Rows: 614 samples
- Target: Loan_Status (Approved/Rejected)

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn (Random Forest)
- Streamlit (Deployment)
- Google Colab

## 🧠 ML Workflow
1. Data Loading & Exploration
2. Missing Value Treatment
3. Exploratory Data Analysis (EDA)
4. Feature Engineering (EMI, Total_Income, EMI_Income_Ratio)
5. Label Encoding
6. Model Training & Comparison
7. Model Evaluation (Accuracy: 82%)
8. Model Saving (Pickle)
9. Streamlit App Deployment

## 🤖 Models Used & Results
| Model | Accuracy |Precision|Recall|F1 Score|
|---|---|
| Logistic Regression | 79% |75%|98%|85%|
| Decision Tree | ~75% |84%|80%|82%|
| Random Forest | 82% ✅ Best |76%|96%|85%|

## 📈 Key Insights
- Credit History is the #1 predictor of loan default
- EMI to Income ratio above 40% significantly increases risk
- Higher total income reduces default probability

## 💻 How to Run Locally
pip install -r requirements.txt
streamlit run app.py

## 👨‍💻 Author
**Vaibhav Sharma** — Aspiring Data Scientist
- GitHub: https://github.com/Vaibhav3323
- LinkedIn: https://www.linkedin.com/in/vaibhav-s-sharma-8b81b929a

💳 Credit Risk - Loan Default Prediction System

After weeks of learning Data Science, I built and deployed 
a complete End-to-End ML project that predicts whether a 
bank should approve or reject a loan application!

🧠 What I built:
✅ Cleaned real-world financial data
✅ Built 3 ML models & compared them
✅ Random Forest gave 82% accuracy
✅ Deployed live using Streamlit
