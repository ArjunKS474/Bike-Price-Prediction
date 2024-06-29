# Diabetes Prediction Using Logistic Regression

This project is aimed at predicting the onset of diabetes in patients using logistic regression.

# Dataset

The dataset used for this project includes the following columns:
- pregnancies: Number of times pregnant
- glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
- diastolic: Diastolic blood pressure (mm Hg)
- triceps: Triceps skinfold thickness (mm)
- insulin: 2-Hour serum insulin (mu U/ml)
- bmi: Body mass index (weight in kg/(height in m)^2)
- dpf: Diabetes pedigree function
- age: Age (years)
- diabetes: Class variable (0 or 1)

# Library Packages

- pandas
- scikit-learn
- numpy
- matplotlib

# Steps:

**1. Data Preprocessing**
- Load the dataset.
- Handle missing values by imputing or removing them.
- Normalize or standardize the data if necessary.
  
**2. Feature Selection**
- Analyze the features and their correlation with the target variable.
- Select features that contribute the most to the prediction.
  
**3. Model Training**
- Split the data into training and testing sets.
- Train the logistic regression model using the training set.
- Tune hyperparameters to improve model performance.
  
**4. Model Evaluation**
- Use the testing set to evaluate the model.
- Calculate accuracy, precision, recall, and F1-score.
- Plot the ROC curve and calculate the AUC.

# Conclusion

Logistic regression effectively predicts diabetes using patient data, achieving reliable performance metrics. This model aids in early detection and management of diabetes.
