# EMI Approval Prediction System

## 📌 Project Overview
This project is an end-to-end Machine Learning application that predicts whether a loan EMI will be approved or not based on customer financial and demographic information. The project covers the complete ML lifecycle including data cleaning, exploratory data analysis, feature engineering, model training, and deployment using Streamlit.

---

## 🚀 Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Streamlit
- MLflow (for experiment tracking)
- Matplotlib, Seaborn

---

## 📂 Project Structure# EMIPredict-AI
End-to-end Machine Learning project for EMI approval prediction using Streamlit and Scikit-learn pipeline
EMIPredict-AI/ ├── data/ │   └── processed/ ├── notebooks/ │   ├── 01_data_cleaning.ipynb │   ├── 02_eda.ipynb │   ├── 03_feature_engineering.ipynb │   └── 04_modeling.ipynb ├── src/ │   ├── preprocessing.py │   ├── feature_engineering.py │   ├── train_models.py │   └── utils.py ├── streamlit_app/ │   └── app.py ├── README.md ├── requirements.txt                                                                                                                                                                                                                            ---

## 🧪 Machine Learning Workflow
1. **Data Cleaning** – Handling missing values, outliers, and data inconsistencies
2. **EDA** – Statistical and visual analysis of features
3. **Feature Engineering** – Encoding categorical variables and scaling numerical features
4. **Model Training** – Logistic Regression using a Scikit-learn pipeline
5. **Evaluation** – Model evaluated using classification metrics
6. **Deployment** – Interactive UI built using Streamlit

---

## 🖥️ Streamlit Application
The Streamlit app allows users to input loan details such as:
- Loan Amount
- Interest Rate
- Loan Tenure

Based on the trained model, the app predicts whether the EMI is approved or not.

---

## ⚠️ Note on Data & Model Files
Due to GitHub file size limitations:
- Large datasets
- Trained model (`.pkl`)
- MLflow artifacts

are **not uploaded** to this repository.

However, all preprocessing steps, model training logic, and deployment code are fully included.

---

## ▶️ How to Run the Project Locally
```bash
pip install -r requirements.txt
streamlit run streamlit_app/app.py                                                                                                                                                                                                                                                                                                                                                     Aarohi Soni
End-to-end Machine Learning Project
