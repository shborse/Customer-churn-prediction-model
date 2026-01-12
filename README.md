Customer Churn Prediction

A Python project that predicts customer churn using machine learning. This project helps businesses identify customers who are likely to leave, enabling proactive retention strategies.

Features

Data preprocessing and cleaning

Exploratory Data Analysis (EDA) for insights

Encoding categorical variables and scaling numeric features

Model training and prediction using Logistic Regression, Random Forest, XGBoost

Save/load trained model and scaler for predictions

Optional Streamlit web app for interactive user input

Dataset

Telco customer dataset

Features: gender, SeniorCitizen, Partner, Dependents, tenure, PhoneService, MultipleLines, InternetService, MonthlyCharges, TotalCharges

Target: Churn (Yes/No)

Installation

Clone the repository:

git clone https://github.com/shborse/customer-churn-prediction.git
cd customer-churn-prediction


Create and activate a virtual environment:

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


Optional: Run Streamlit web app:

streamlit run app.py


Open http://localhost:8501 in your browser to use the interactive interface.

Technologies

Python, Pandas, NumPy

Scikit-learn, Joblib

Jupyter Notebook

Matplotlib, Seaborn

Streamlit (optional web app)

Folder Structure
customer-churn-prediction/
│
├── churn_model.pkl        # Saved ML model
├── scaler.pkl             # Feature scaler
├── predict_churn.py       # Script to predict churn
├── app.py                 # Optional Streamlit app
├── notebooks/             # Jupyter notebooks
├── data/                  # Dataset files
├── requirements.txt       # Dependencies
└── README.md
