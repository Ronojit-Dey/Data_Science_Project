📊 Predicting Mobile Phone Prices in India using Machine Learning
🔎 Overview

This project explores the factors influencing mobile phone prices in India and builds a Random Forest Regression model to predict prices based on various specifications.

The workflow includes:

Exploratory Data Analysis (EDA)

Data Preprocessing (cleaning & scaling)

Model Building (Random Forest with hyperparameter tuning)

Model Evaluation (R², MAE, RMSE, and Cross-Validation)

Insights on which features drive mobile phone prices

🚀 Features

Data Analysis & Visualization: Distribution, feature importance, and correlations

Random Forest Regression: Trained with hyperparameter tuning (GridSearchCV)

Model Evaluation: R², MAE, RMSE, and Cross-Validation R²

Feature Importance Insights: Identifying what impacts mobile phone pricing the most

Saved Model: Exported trained model for reuse

🛠️ Tech Stack

Python

Pandas, NumPy → Data manipulation

Matplotlib, Seaborn → Data visualization

Scikit-learn → ML model building & evaluation

📂 Project Structure
Mobile-Price-Prediction/
│── data/                # Dataset (CSV file)
│── notebooks/           # Jupyter notebooks with step-by-step code
│── models/              # Saved trained model (Random Forest)
│── results/             # Evaluation results, charts, and feature importances
│── README.md            # Project documentation
│── requirements.txt     # Required dependencies

📊 Results

Best Model: Random Forest Regressor

R² Score (Train/Test Split): ~0.82

Cross-Validation R²: ~0.80

MAE: ~0.18

RMSE: ~0.26

📌 Interpretation: The model explains ~82% of the variance in mobile phone prices, performing well across multiple folds (CV R² ~80%).

💡 Key Insights

RAM, Processor, and Battery are major drivers of price.

Brand & screen size show secondary but noticeable influence.

Random Forest was chosen due to its robustness, ability to handle non-linear relationships, and feature importance insights.

🔧 Installation & Usage

Clone the repo:

git clone https://github.com/your-username/mobile-price-prediction.git
cd mobile-price-prediction


Install dependencies:

pip install -r requirements.txt


Run the Jupyter notebook:

jupyter notebook

🎯 Future Improvements

Try other models (XGBoost, Gradient Boosting, Neural Networks)

Perform feature engineering for categorical data

Build a web app (Streamlit/Flask) to predict prices interactively

🤝 Contribution

Contributions are welcome! Feel free to fork this repo, open issues, or submit pull requests.
