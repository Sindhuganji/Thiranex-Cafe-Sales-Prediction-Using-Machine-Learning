# Cafe Sales Prediction Using Machine Learning

A Python-based Machine Learning project focused on predicting cafe sales using regression algorithms such as Linear Regression, Decision Tree Regressor, and Random Forest Regressor.

---

## Project Overview

This project uses a real-world cafe sales dataset containing:
- Missing values
- Invalid entries
- Mixed data types
- Categorical and numerical features

The dataset is cleaned and preprocessed before applying Machine Learning models to predict customer spending and analyze sales behavior.

---

## Features

- Data Cleaning & Preprocessing
- Feature Engineering
- Label Encoding
- Exploratory Data Analysis
- Regression Modeling
- Model Evaluation
- Feature Importance Analysis
- Visualization of Predictions

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

---

## Dataset

Dataset used:
- dirty_cafe_sales.csv

### Dataset Columns
- Transaction ID
- Item
- Quantity
- Price Per Unit
- Total Spent
- Payment Method
- Location
- Transaction Date

---

## Objectives of the Project

- Preprocess and clean real-world data
- Train Machine Learning models
- Predict total customer spending
- Compare regression model performance
- Evaluate models using regression metrics

---

## Data Preprocessing Steps

### 1. Handling Missing Values
- Filled missing values using statistical methods

### 2. Removing Invalid Entries
Replaced:
- ERROR
- UNKNOWN

with null values.

### 3. Data Type Conversion
Converted numerical columns into numeric format.

### 4. Encoding Categorical Variables
Applied Label Encoding for machine learning compatibility.

### 5. Feature Engineering
Created additional features from transaction dates.

---

## Machine Learning Models Used

### 1. Linear Regression
Baseline regression model for prediction.

### 2. Decision Tree Regressor
Captures nonlinear relationships in data.

### 3. Random Forest Regressor
Ensemble learning model for improved accuracy.

---

## Model Evaluation Metrics

The models were evaluated using:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

Higher R² Score indicates better prediction performance.

---

## Visualizations Included

### 1. Actual vs Predicted Values
Scatter plot comparing predictions with actual values.

### 2. Feature Importance Graph
Shows important features affecting predictions.

### 3. Correlation Heatmap
Displays relationships between numerical variables.

### 4. Sales Trend Analysis
Line graph showing sales behavior over time.

---

## Sample Workflow

text Raw Dataset      ↓ Data Cleaning      ↓ Feature Engineering      ↓ Encoding      ↓ Train-Test Split      ↓ Model Training      ↓ Model Evaluation      ↓ Prediction & Visualization 

---

## Key Insights Generated

Some insights identified:
- Products influencing total sales
- Relationship between quantity and spending
- Best-performing regression model
- Important predictive features
- Customer purchase patterns

---

## How to Run the Project

### 1. Clone the Repository

bash git clone https://github.com/Sindhuganji/Cafe-Sales-Prediction-Using-Machine-Learning.git 

### 2. Navigate to Project Folder

bash cd Cafe-Sales-Prediction-Using-Machine-Learning 

### 3. Install Required Libraries

bash pip install pandas numpy matplotlib seaborn scikit-learn 

### 4. Run the Python File

bash python cafe_sales_prediction_using_machine_learning.py 

---

## Learning Outcomes

Through this project, I learned:
- Machine Learning workflow implementation
- Data preprocessing techniques
- Feature engineering
- Regression modeling
- Model evaluation methods
- Data visualization and interpretation

---

## Future Improvements

- Hyperparameter tuning
- Cross-validation
- XGBoost implementation
- Streamlit web app deployment
- Real-time prediction system

---

## Author

### Pushpa Sri Sindhu
- BTech CSE, SRM AP University
- BS Data Science and Applications, IIT Madras

GitHub:
https://github.com/Sindhuganji

---

## License

This project is open-source and available for educational and learning purposes.
