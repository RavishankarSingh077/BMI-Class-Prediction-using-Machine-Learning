# BMI-Class-Prediction-using-Machine-Learning

Project Title: BMI Class Prediction using Machine Learning

Project Description:

This project focuses on predicting an individual's Body Mass Index (BMI) class using machine learning techniques. The dataset used contains attributes such as Age, Height, Weight, and the corresponding BMI value and BMI category (e.g., Normal, Overweight, Obese Class 1, etc.).

Objective:

The primary objective of this project is to build a regression model that can accurately predict a person's BMI and categorize it into one of the six BMI classes:

Underweight

Normal Weight

Overweight

Obese Class 1

Obese Class 2

Obese Class 3

Steps Followed:

Data Preprocessing:

Loaded and explored the dataset with 741 entries.

Verified there were no missing values.

Encoded BMI categories into numeric labels (0 to 5).

Handled outliers using IQR and z-score techniques.

Scaled the features (Age, Height, Weight) using StandardScaler.

Model Training:

Split the dataset into training and testing sets using an 70:30 ratio.

Applied Linear Regression to predict BMI values.

Model Evaluation:

Achieved a high prediction accuracy with an R² score of 97.92% on the test data.

The model showed strong generalization capabilities on unseen data.

Model Deployment:

Saved the trained model using joblib.

Built a BMI class prediction function that takes user input and predicts their BMI class.

Technologies & Libraries Used:

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn (LinearRegression, train_test_split, StandardScaler, r2_score)

Joblib for model persistence

Conclusion:

This project successfully demonstrates the ability to predict BMI classes with high accuracy using simple linear regression techniques. The model can assist in basic health screening or serve as a component in larger health analytics systems.
