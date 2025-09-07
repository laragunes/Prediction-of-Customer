# 📊 Multiple Linear Regression - Restaurant Customer Prediction

This project applies a **Multiple Linear Regression** model to predict the **daily number of customers** visiting a restaurant.  
The model uses independent variables such as **weather conditions, day of the week, whether it is a special day, and the advertising spend** to estimate customer counts.

## 🔹 Objective
To predict restaurant customer flow based on multiple factors that influence demand, such as weather, weekdays, holidays/events, and marketing spending.

## 🔹 Dataset
The dataset is provided as a **CSV file** in the repository.  
👉 You can directly run the project with this CSV dataset.  

It includes:  
- `Weather_Condition` (e.g.,which degree)  
- `Day_of_Week` (e.g., Monday–Sunday or 0–6 numeric code)  
- `Special_Day` (0 = no, 1 = special day/holiday)  
- `Ad_Spend` (advertising budget allocated)  
- `customers` (target variable – daily customer count)  

## 🔹 Features
- Load and preprocess data from CSV file  
- Encode categorical features and handle missing values  
- Train a multiple linear regression model  
- Predict restaurant customer counts  
- Evaluate model performance (R², MAE, RMSE)  
- Visualize predictions vs. actual values  

## 🔹 Tech Stack
- Python 🐍  
- NumPy  
- Pandas  
- scikit-learn  
- Matplotlib / Seaborn  

## 🔹 How to Run
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/multiple-linear-regression-restaurant-customers.git

2. Navigate to the project folder:
    ```bash
   cd multiple-linear-regression-restaurant-customers

3. Run the script (make sure the dataset CSV file is in the same folder):
    ```bash
   python "multiple_linear_regression(1).py"
    
## 🔹  Use Cases
Forecasting daily operations (staffing, inventory, scheduling)

Evaluating advertising budget effectiveness

Planning for holidays and special events

Adjusting capacity based on weather impact

✍️ Author: *Ayşe Lara Güneş*

    



