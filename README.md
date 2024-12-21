                                    DIABETES PREDICTION MODEL


OVERVIEW

A Support Vector Machine (SVM) model designed to predict diabetes based on features such as age, blood pressure, and glucose levels. The implementation uses Python libraries like NumPy and scikit-learn for data processing, standardization, and training.

MODEL FUNCTIONALITY:

Data Preprocessing: Reshapes and standardizes input data.
Model Training: Employs an SVM model with a linear kernel.
Prediction: Outputs diabetes status based on input features.


DATASET FEATURES:

Pregnancies
Glucose
BloodPressure 
SkinThickness  
Insulin
BMI
DiabetesPedigreeFunction
Age  
Diabetes Status (0 = Not Diabetic, 1 = Diabetic)


INSTALLATION:
bash
Copy code
pip install numpy scikit-learn
Usage
Train the Model
Run the script with the dataset to train the SVM model.

Make Predictions
Provide new input data to predict diabetes status:
inputs=(4,110,92,0,0,37.6,0.191,30)
