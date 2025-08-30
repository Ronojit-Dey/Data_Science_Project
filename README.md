# 📱 Mobile Price Prediction: Understanding Key Factors Behind Rising Costs in India using Random Forest Algorithm

## 📖 Overview
This project explores the factors influencing mobile phone prices in India. Using **EDA, feature engineering, and Random Forest Regression**, the model predicts prices and identifies the most significant contributors.  
The aim is not just prediction but also **explainability** – uncovering what drives mobile pricing trends.

---

## ⚙️ Tech Stack
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn (Random Forest, GridSearchCV, Cross-validation)
- Jupyter Notebook

---

## 📂 Project Structure
```plaintext
Mobile-Price-Prediction/
│── data/
│ └── mobile_prices.csv # Dataset
│── notebooks/
│ └── analysis.ipynb # Main Jupyter notebook
│── models/
│ └── best_rf_model.pkl # Saved Random Forest model
│── README.md # Project documentation
```

---

## 🔑 Key Steps
1. **Data Loading & Cleaning** – Preparing the dataset for analysis.  
2. **Exploratory Data Analysis (EDA)** – Understanding price distributions & patterns.  
3. **Preprocessing** – Feature scaling, encoding, handling missing values.  
4. **Model Training** – Random Forest with hyperparameter tuning.  
5. **Evaluation** – R² Score, Cross-validation, visualization of results.  
6. **Model Saving** – Exporting the trained model for future use.  

---

## 📊 Results
- **Best R² Score (Train):** 0.95+  
- **Cross-validation R² Score (CV):** ~0.89  
- **Key Factors Driving Price:** Battery capacity, RAM, storage, processor speed, brand effect.  

---

Install dependencies: 
  ```bash

pip install -r requirements.txt
```

Open Jupyter Notebook:

jupyter notebook


Run analysis.ipynb to see the results.

📌 Future Improvements

Try XGBoost / LightGBM for performance comparison.

Add SHAP / LIME explainability for deeper insights.

Deploy as a Streamlit web app for interactive predictions.

✨ Author

Developed by Your Name (BCA Final Year Project)



