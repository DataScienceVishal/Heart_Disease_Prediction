# Heart Disease Prediction Case Study

## Problem Statement
The objective is to predict whether a patient has or will develop heart disease based on several medical attributes.

## About the Data
| Variable     | Description                              |
|--------------|------------------------------------------|
| age          | Age of the patient                       |
| sex          | Gender of the patient (0: Female, 1: Male) |
| BP           | Blood pressure of the patient            |
| cholestrol   | Cholesterol level of the patient         |
| heart disease| Target variable indicating presence of heart disease (0: No, 1: Yes) |

## Modeling Approach
Decision Tree and Random Forest algorithms were utilized for building the predictive models. 

### Features Importance
The models provided insights into the significant factors influencing heart disease prediction. Age was identified as the most important feature, indicating its strong influence on the presence of heart disease.

### Hyperparameter Tuning
GridSearchCV was employed for hyperparameter tuning to optimize model performance.

### Visualization
Graphviz was utilized to visualize decision trees for better interpretation of the models.

## Libraries Used
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- graphviz
- Ipython
- six
- pydotplus
