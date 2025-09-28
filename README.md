# RCCS: Regression for Concrete Compressive Strength

This project predicts **Concrete Compressive Strength (RCCS)** using machine learning techniques. It is implemented in a Jupyter Notebook and can be deployed as a simple Flask web app via ngrok.  

## 📌 Features
- Load dataset (UCI Concrete Compressive Strength or custom upload).  
- Perform Exploratory Data Analysis (EDA) with visualizations.  
- Train ML models with scaling and hyperparameter tuning.  
- Save and reuse trained pipelines with joblib.  
- Deploy model using **Flask + ngrok** for web access.  

## 🛠️ Technologies Used
- **Python** (pandas, numpy, matplotlib, seaborn)  
- **scikit-learn** (train/test split, GridSearchCV, RandomForestRegressor, pipelines)  
- **Flask + Flask-CORS** (for web API)  
- **ngrok** (to expose Flask server)  
- **joblib** (model persistence)  

## 🚀 Getting Started

### 1. Clone Repository
```bash
git clone https://github.com/your-username/RCCS.git
cd RCCS
