# House Price Prediction (ML Pipeline + Streamlit)

A machine learning web application that predicts house prices using a full preprocessing and modeling pipeline.  
The project uses ColumnTransformer, StandardScaler, OneHotEncoder, and RandomForestRegressor.

---

## Features

- Full ML pipeline (preprocessing + model)
- Handles numerical and categorical features automatically
- Feature scaling and encoding included
- Random Forest model for better performance
- Interactive web app using Streamlit

---

## How It Works

1. Load dataset using pandas  
2. Select features:
   - Numerical:
     - OverallQual
     - GrLivArea
     - GarageCars
     - TotalBsmtSF  
   - Categorical:
     - HouseStyle
     - RoofStyle  
3. Split data into training and testing sets  
4. Preprocessing:
   - StandardScaler for numerical features  
   - OneHotEncoder for categorical features  
5. Build pipeline:
   - Preprocessing → Model  
6. Train model using RandomForestRegressor  
7. User inputs data via Streamlit  
8. Pipeline automatically processes input and predicts price  

---

## Input Features

- Overall Quality
- Ground Living Area
- Garage Capacity
- Basement Area
- House Style
- Roof Style

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit

---
