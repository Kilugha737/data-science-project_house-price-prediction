# data-science-project_house-price-prediction
🏡 House Price Prediction Challenge
This repository contains a complete end-to-end machine learning workflow to solve a real-world House Price Prediction problem using a dataset from Kaggle. The project focuses on data wrangling, exploratory data analysis, feature engineering, model building, hyperparameter tuning, and model evaluation.

📊 Project Overview
The goal is to predict house prices (in Lakhs) based on several property-related features, such as square footage, number of rooms, location, and more. A Random Forest Regressor was trained using an optimized pipeline, and the best model was selected through GridSearchCV.

🔍 Key Highlights
📥 Dataset downloaded using kagglehub

🧹 Custom wrangle() function for preprocessing and cleaning

🧠 Baseline model with DummyRegressor

⚙️ Full pipeline: imputation → scaling → encoding → regression

🧪 Cross-validation and hyperparameter tuning with GridSearchCV

📈 Evaluation using RMSE and R² metrics

🗺️ Feature importance analysis and visualization

📦 Model serialization using joblib

🧾 Reusable prediction function for new data

🛠️ Technologies Used
Python (3)

Pandas, NumPy, Seaborn, Matplotlib, Plotly

Scikit-learn (Pipeline, RandomForestRegressor, GridSearchCV)

Scipy (for statistical tests)

Joblib (for model persistence)

📈 Results
Best cross-validated RMSE: ~19.36

Test RMSE: ~19.54

Test R²: ~0.76

Most important features: SQUARE_FT, LONGITUDE, LATITUDE, and location-related encodings

🚀 How to Use
Clone the repository

Install dependencies

Run the Jupyter notebook or use the provided .py scripts

Use the make_predictions() function to generate predictions on new data

📌 Future Work
Try advanced models (e.g., XGBoost, LightGBM)

Deploy the model as an API (e.g., with FastAPI or Flask)

Integrate with streamlit for interactive dashboard

📬 Contact
Feel free to open an issue or reach out if you have suggestions or questions!
