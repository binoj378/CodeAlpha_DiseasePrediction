Disease Prediction from Medical Data

Project Overview:

The objective of this project is to predict the possibility of a disease based on patient medical data using machine learning classification techniques. In this implementation, the **Heart Disease Dataset** was used to predict whether a patient is likely to have heart disease.

Machine learning helps analyze patient health parameters and identify patterns that may indicate disease risk.



Objective:

To build a machine learning model that predicts the presence of heart disease based on structured medical data such as:

* Age
* Sex
* Chest Pain Type
* Blood Pressure
* Cholesterol Level
* Blood Sugar
* ECG Results
* Heart Rate
* Exercise-Induced Angina

Dataset:

Dataset used: Heart Disease Dataset (Kaggle)

The dataset contains medical records of patients with multiple health-related features and a target column indicating disease presence.

* 0 → No Heart Disease
* 1 → Heart Disease Present

Technologies Used:

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Scikit-learn



Machine Learning Algorithm Used:

The classification model used in this project:

* Logistic Regression

Project Workflow:

 1. Data Collection

Downloaded the Heart Disease dataset from Kaggle and uploaded it into Google Colab.

 2. Data Preprocessing

Performed basic preprocessing:

* Loaded dataset using Pandas
* Checked dataset shape
* Checked for missing values
* Split input and output features

 3. Train-Test Split

Dataset was divided into:

* 80% Training Data
* 20% Testing Data

 4. Model Training

Trained the Logistic Regression model using training data.

5. Prediction

Used the trained model to predict disease risk on test data.

 6. Evaluation

Evaluated model performance using accuracy score.



Model Performance

Final Accuracy Achieved:

 79%

This means the model correctly predicted disease presence for approximately 79 out of 100 test cases.



 Output

The model predicts whether a patient has heart disease based on medical input data.

Example Output:

* Prediction = 0 → No Disease
* Prediction = 1 → Disease Risk Present



Conclusion:

This project demonstrates how machine learning can be used in healthcare for early disease prediction. Even with a basic classification model, useful prediction accuracy was achieved.

Future improvements may include:

* Using Random Forest
* Using SVM
* Feature Scaling
* Hyperparameter Tuning
* Testing on larger dataset
