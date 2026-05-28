# Cafe-Sales-Prediction-Using-Machine-Learning

A Machine Learning project that predicts cafe sales using regression algorithms such as Linear Regression, Decision Tree Regressor, and Random Forest Regressor. This project demonstrates data cleaning, preprocessing, feature engineering, model training, evaluation, and visualization using Python.

⸻

Project Overview

This project uses a real-world messy cafe sales dataset containing:

* Missing values
* Invalid entries
* Mixed data types
* Categorical and numerical features

The dataset is cleaned and processed before applying Machine Learning models to predict the Total Spent by customers.

⸻

Features

* Data Cleaning & Preprocessing
* Handling Missing Values
* Encoding Categorical Variables
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Regression Modeling
* Model Evaluation
* Data Visualization
* Feature Importance Analysis

⸻

Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook / Google Colab

⸻

Machine Learning Models Used

1. Linear Regression

A basic regression model used as a baseline.

2. Decision Tree Regressor

Captures nonlinear relationships in the data.

3. Random Forest Regressor

An ensemble learning method that improves prediction accuracy.

⸻

Dataset

Dataset used:

* dirty_cafe_sales.csv

Dataset Columns

* Transaction ID
* Item
* Quantity
* Price Per Unit
* Total Spent
* Payment Method
* Location
* Transaction Date

⸻

Data Preprocessing Steps

* Replaced invalid values (ERROR, UNKNOWN) with NaN
* Converted numerical columns to numeric types
* Handled missing values
* Encoded categorical variables
* Removed duplicates
* Processed date columns
* Feature extraction from transaction dates

⸻

Exploratory Data Analysis

Visualizations included:

* Most sold items
* Revenue by item
* Payment method distribution
* Correlation heatmap
* Sales trends over time
* Feature importance graph
* Actual vs Predicted values

⸻

Model Evaluation Metrics

The models were evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* R² Score

Higher R² Score indicates better model performance.

⸻

Project Workflow

Dataset
   ↓
Data Cleaning
   ↓
Feature Engineering
   ↓
Encoding
   ↓
Train-Test Split
   ↓
Model Training
   ↓
Evaluation
   ↓
Visualization
   ↓
Prediction System

⸻

Sample Visualizations

Correlation Heatmap

Shows relationships between numerical variables.

Actual vs Predicted Plot

Compares model predictions with actual sales values.

Feature Importance

Displays the most influential features affecting predictions.

⸻

How to Run the Project

1. Clone the Repository

git clone https://github.com/Sindhuganji/Cafe-Sales-Prediction-Using-Machine-Learning.git

2. Navigate to Project Folder

cd Cafe-Sales-Prediction-Using-Machine-Learning

3. Install Required Libraries

pip install pandas numpy matplotlib seaborn scikit-learn

4. Run the Python File

python cafe_sales_prediction_using_machine_learning.py

⸻

Future Improvements

* Hyperparameter tuning
* Cross-validation
* XGBoost implementation
* Streamlit web app deployment
* Power BI dashboard integration
* Real-time prediction system

⸻

Learning Outcomes

Through this project, I learned:

* Real-world data preprocessing
* Data visualization techniques
* Regression algorithms
* Model evaluation methods
* Feature engineering
* Machine Learning workflow implementation

⸻

Author

Pushpa Sri Sindhu

* BTech CSE, SRM AP University
* BS Data Science, IIT Madras

GitHub:
Sindhuganji GitHub Profile￼

⸻

License

This project is open-source and available for educational purposes.
