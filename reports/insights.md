# Project Insights

## Dataset Overview
This project uses the student performance in exam dataset having demographic and academic features of 1000 students.
It includes features such as gender, race/ethnicity, parental level of education, lunch, test preparation course, math score, reading score, and writing score.
[Dataset Download](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams/discussion?sort=hotness)

## Key Observations
- Reading and writing scores are highly correlated.
- Students receiving standard lunch and completing test preparation course generally performed better.

## Model Performance
- Linear regression outperformed Random Forest Regressor on this dataset.
- However, the relatively low R2 score indicates that the available features explain only a limited portion of the variation in student performance.
- For Linear regression:
  - MAE : 10.490182374209294
  - MSE : 179.60234233623538
  - RMSE: 13.401579844788277
  - R²  : 0.16217185763155217
- For Radom Forest Regressor:
  - R²: -0.01861419507194917
 
## Limitations
- Additional important features like study hours, sleep hours, and previous academic report are missing.
- Dataset is small and less diverse.

## Future Scope
- Introduce additional important features like study hours, sleep hours, and previous academic report.
- Collect a larger and more diverse dataset.
- Deploy the Model as an interactive web application using Streamlit.

## Lessons Learnt
- Feature quality is more important than model complexity.
- EDA helped identify important relationships before model training.
- Complex models do not always outperform simpler models.
