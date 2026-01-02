# 🏠 House Price Prediction using XGBoost Regression

This project uses **XGBoost Regression** to predict **house prices** based on multiple numerical features related to housing, location, and socio-economic factors.
The model is trained on the **Boston Housing dataset** (BostonHousing.csv) to estimate continuous house price values accurately.


## 📘 Project Overview

This is a **Supervised Machine Learning** based **Regression** project.
By analyzing various housing attributes, the model predicts the **median value of owner-occupied homes**.
The goal is to build an efficient, accurate, and reliable house price prediction system using **XGBoost Regressor**.


## 🗂️ Dataset Information

**Dataset Name:** Boston Housing Dataset  
**Format:** CSV file (BostonHousing.csv)

### Columns
- **CRIM** → Crime rate
- **ZN** → Proportion of residential land
- **INDUS** → Non-retail business acres
- **CHAS** → Charles River dummy variable
- **NOX** → Nitric oxide concentration
- **RM** → Average number of rooms
- **AGE** → Proportion of old houses
- **DIS** → Distance to employment centers
- **RAD** → Accessibility to highways
- **TAX** → Property tax rate
- **PTRATIO** → Pupil-teacher ratio
- **B** → Proportion of Black population
- **LSTAT** → Percentage of lower-status population

### Target Variable
- **price** → House price


## 🧠 Technologies Used

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost


## ⚙️ Project Workflow

1. Load the dataset using Pandas
2. Perform Exploratory Data Analysis (EDA)
3. Check missing values using isnull().sum()
4. Analyze feature correlation using a heatmap
5. Split features and target
   - X → All columns except price
   - Y → price
6. Split the data into 80% training and 20% testing
7. Train the model using XGBRegressor
8. Evaluate model performance using:
   - R² Score
   - Mean Absolute Error (MAE)
9. Visualize actual vs predicted house prices
10. Predict house prices for custom input values


## 📊 Example Output

Training Data:
- R squared error : High
- Mean Absolute Error : Low

Testing Data:
- R squared error : Slightly lower than training
- Mean Absolute Error : Acceptable

This indicates that the model performs well and generalizes effectively on unseen data.


## 🧪 Predicting Custom Input

You can edit this variable inside the code:

input_data = (0.02985, 0, 2.18, 0, 0.458, 6.43, 58.7, 6.0622, 3, 222, 18.7, 394.12, 5.21)

Output:
Predicted House Price: <numeric value>


## 👨‍💻 Author

Developed by **Saurabh**

Feel free to connect or contribute to this project!

⭐ If you found this project helpful, don’t forget to star the repository!
