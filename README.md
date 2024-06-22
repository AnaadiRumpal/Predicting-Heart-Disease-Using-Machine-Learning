# Predicting-Heart-Disease-Using-Machine-Learning
This project focuses on using machine learning and data science techniques to predict the presence of heart disease based on various medical attributes of patients.

## 1. Problem Definition:
The goal is to predict whether a patient has heart disease based on clinical parameters such as age, sex, cholesterol levels, and other medical attributes. This is a classification problem where the target variable is binary (1 for presence of heart disease, 0 for absence).

## 2. Data Sources:

The original dataset is sourced from the Cleveland database from the UCI Machine Learning Repository.
An alternative version of the dataset is also available on Kaggle, providing accessibility and multiple resources for data validation and comparison.

## 3. Evaluation Metric:
The model's performance is evaluated based on accuracy, aiming for at least 95% accuracy during the proof of concept phase to proceed with the project.

## 4. Features:
The dataset includes several features that describe a patient's health status:

Demographic: Age, sex
Medical Parameters: Resting blood pressure, cholesterol levels, fasting blood sugar, maximum heart rate achieved, exercise-induced angina, ST depression induced by exercise, number of major vessels colored by fluoroscopy, thalium stress test result, etc.

## 5. Tools and Technologies Used:
The project utilizes Python-based libraries for data analysis, visualization, and machine learning:

### Data Analysis: 
Pandas, NumPy

### Visualization: 
Matplotlib, Seaborn

### Machine Learning Models: 
Logistic Regression, K-Nearest Neighbors Classifier, Random Forest Classifier from Scikit-Learn

### Model Evaluation: 
Cross-validation, confusion matrix, precision, recall, F1-score

## 6. Data Exploration and Preprocessing:

Conducted exploratory data analysis (EDA) to understand the dataset's characteristics, distribution of features, and identify any patterns or correlations.
Handled missing data (none found) and checked for outliers.
Converted categorical variables into numerical format as needed.

## 7. Modeling and Evaluation:

### Model Selection: 
Evaluated multiple machine learning algorithms (Logistic Regression, KNN, Random Forest) to determine the best-performing model for predicting heart disease.

### Model Training: 
Split the data into training and testing sets (80% training, 20% testing) using random seed for reproducibility.

### Model Training and Evaluation: 
Trained each model on the training set and evaluated its performance on the test set using accuracy as the primary metric.

### Model Comparison: Used  3 different machine learning models:
'Logistic Regression': 0.8852459016393442,
 'KNN': 0.6885245901639344,
 'Random Forest': 0.8360655737704918

###Model Improvisation: Did Hypyterparameter tuning using 
- by hand 
- RandomizedSearchCV on LogisticRegression()
RandomForestClassifier() 
- GridSearchCV on LogisticRegression Model as it provided best score.


## 8. Results:

Model Performance: Achieved 88.52% accuracy on the test set with the best-performing model Logistic Regression. Analysed result with 
confusion Matrix, 
cross validation with precision of 84.46%, precision 82.07%, recall 92.12% and f1 score of 86.73%.


## Conclusion:
This project showcases the application of machine learning in healthcare, specifically in predicting heart disease based on patient data. The results underscore the potential of data-driven approaches to assist in early detection and management of cardiovascular conditions.

