# E-commerce-Sales-Prediction-ML-EDA-
Skills: EDA, feature engineering, regression models, forecasting Build:  Analyze customer purchase patterns  Predict next-month revenue  Use RandomForest/XGBoost
E-commerce Sales Prediction —  Project Structure
📁 ecommerce-sales-prediction/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── data/
│   ├── Ecommerce_Sales_Prediction_Dataset.csv
│   └── processed_data.csv
│
├── notebooks/
│   └── ecommerce_sales_eda_and_forecasting.ipynb
│
├── models/
│   ├── random_forest_model.pkl
│   └── xgboost_model.pkl
│
├── outputs/
│   ├── revenue_trend.png
│   ├── correlation_heatmap.png
│   ├── product_category_distribution.png
│   └── next_month_forecast.csv
│
├── src/
│   ├── data_loader.py
│   ├── eda.py
│   ├── features.py
│   ├── train.py
│   ├── predict.py
│   └── utils.py
│
└── app/
    └── streamlit_app.py

# 📈 E-commerce Sales Prediction (ML + EDA)

A complete Machine Learning project to analyze e-commerce sales data, perform exploratory data analysis (EDA), engineer features, train ML models, and forecast next-month revenue using **RandomForest** and **XGBoost**.

This project is beginner-friendly and perfect for ML/Data Science portfolios.

---

## 🚀 Features

- Full **Exploratory Data Analysis (EDA)**
- Revenue trend visualization
- Category & segment analysis
- Feature engineering scripts
- RandomForest + XGBoost regression
- Next-month revenue forecasting
- Streamlit dashboard
- Modular `src/` code structure
- Auto-generated notebook + PNG charts

---

## 🗂️ Project Structure
ecommerce-sales-prediction/
├── data/ # Raw & processed data
├── notebooks/ # EDA + model notebook
├── models/ # Trained ML models
├── outputs/ # Charts + predictions
├── src/ # All python modules
└── app/ # Streamlit UI

---

## 📥 Installation

Clone the repo:

```bash
git clone https://github.com/<your-username>/ecommerce-sales-prediction.git
cd ecommerce-sales-prediction
Install dependencies:
pip install -r requirements.txt
Run the Project
1. Run EDA + Modeling
python src/train.py
2. Generate predictions
python src/predict.py
3. Launch Streamlit Dashboard
streamlit run app/streamlit_app.py
Results

RandomForest + XGBoost trained

MAE & R² scores displayed in terminal

Forecast saved to:
outputs/next_month_forecast.csv
Charts saved in outputs/

🤖 Models Saved
Model	File
RandomForestRegressor	models/random_forest_model.pkl
XGBoostRegressor	models/xgboost_model.pkl
Technologies Used

Python (Pandas, NumPy)

Scikit-Learn

XGBoost

Matplotlib & Seaborn

Streamlit

Joblib

nbformat
Future Enhancements

GridSearchCV hyperparameter tuning

ARIMA/LSTM Forecasting

SHAP model explainability

Web deployment on Render/Streamlit Cloud

👤 Author

Shreyas (Your Name)
Data Scientist & AI Engineer
