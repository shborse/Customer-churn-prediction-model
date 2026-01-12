Customer Churn Prediction

A Python project to predict customer churn using machine learning. This helps businesses identify customers likely to leave.

Features

Data cleaning and preprocessing

Exploratory Data Analysis (EDA)

Model training and prediction (Logistic Regression, Random Forest, XGBoost)

Save/load model for predictions

Optional Streamlit web app

Installation

Clone the repository:

git clone https://github.com/shborse/customer-churn-prediction.git
cd customer-churn-prediction


Create and activate a Python virtual environment:

python -m venv env
# Windows
.\env\Scripts\activate
# macOS/Linux
source env/bin/activate


Install dependencies:

pip install -r requirements.txt

Usage

Run prediction script:

python predict_churn.py


Optional Streamlit app:

streamlit run app.py


Open http://localhost:8501 in your browser.
