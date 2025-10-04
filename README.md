# Customer Churn Prediction

## Project Overview
This project aims to predict **customer churn** for a company using machine learning.  
Customer churn occurs when a customer stops using a company's service.  
By predicting churn in advance, businesses can take proactive measures to **retain customers** and improve revenue.


## Project Structure

customer-churn-prediction/
│
├── data/
│ ├── customer_churn_raw.csv # Original, immutable data
│ ├── customer_churn_cleaned.csv # Cleaned and processed data for modeling
│
├── models/ # Trained and serialized models
│ ├── final_model.pkl # Final trained machine learning model
│ ├── preprocessed.pkl # Preprocessing pipeline saved
│
├── notebooks/ # Jupyter notebooks for EDA and experimentation
│ ├── 01_data_exploration.ipynb # Exploratory Data Analysis
│ ├── 02_data_preprocessing.ipynb # Data cleaning and preprocessing
│ ├── 02_modeling.ipynb # Model training and evaluation
│
├── reports/
│ ├── figures/
│ │ └── all figures
│
└── README.md # Project documentation
|___requirements.txt  # all libraries and modules for this project
|




---

## Tools & Libraries
- Python 3.x  
- pandas  
- numpy  
- scikit-learn  
- joblib  
- matplotlib / seaborn (for visualization)  
- Jupyter Notebook  

## Model Evaluation

- Metrics used: Accuracy, Precision, Recall, F1-score

- Models implemented: Decision Tree, Random Forest, Logistic Regression

- Preprocessing: Scaling numerical features, one-hot encoding categorical and binary features.

### Notes

- Preprocessing pipeline saved in models/preprocessed.pkl for consistent data transformation.

- Final trained model saved in models/final_model.pkl for prediction on new data.

