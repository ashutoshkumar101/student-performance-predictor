# Student Performance Predictor
Machine learning project to predict student performance using demographic and academic features.

## Overview
The goal of this project is to predict a student's overall performance using demographic and academic attributes. The project demonstrates a complete machine learning workflow from exploratory data analysis to model evaluation. The output of this project is the predicted overall performance of a student based on demographic and academic attributes.

## Dataset
This project uses the Student Performance in Exams dataset from Kaggle, which contains demographic and academic information for 1000 students.
- Link: 
- Shape: (1000, 8)

## Technologies Used
- Python
- Numpy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Google Colab

## Workflow
1. Problem Definition
2. Data Acquisition
3. Data Understanding
4. Exploratory Data Analysis (EDA)
5. Data Preprocessing
6. Feature Engineering
7. Model Training
8. Model Evaluation
   
## Models used
  - Linear Regression
  - Random Forest Regressor
  
## Evaluation Metrics
  - MAE
  - RMSE
  - R2 Score

## Key Findings
- Reading and writing scores are highly correlated.
- Students receiving standard lunch and completing the test preparation course generally performed better.
- Linear Regression outperformed Random Forest Regressor on this dataset.

## Future Improvements
- Collect additional features such as study hours, IQ, sleep duration and previous academic performance.
- Increase the size and diversity of the dataset.
- Experiment with advanced regression models such as XGBoost and Gradient Boosting.
- Deploy the model as a web application using Streamlit.

