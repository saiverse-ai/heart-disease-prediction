# AI-Based Health Risk Prediction System

## Project Overview

The AI-Based Health Risk Prediction System is a Machine Learning project designed to predict the possibility of heart disease by analyzing a person's health parameters.

The system uses medical data such as age, gender, cholesterol, blood pressure, maximum heart rate, and other health-related attributes to identify potential heart disease risks.

A Machine Learning model analyzes the input data and predicts whether a person is likely to have heart disease. The system aims to support early risk identification and encourage people to seek medical advice when necessary.

## Objectives

- Predict the possibility of heart disease using Machine Learning.
- Analyze multiple health parameters.
- Identify potential health risks at an early stage.
- Provide prediction results based on user health data.
- Support awareness and preventive healthcare.

## Technologies Used

- **Programming Language:** Python
- **Machine Learning Algorithm:** Random Forest Classifier
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Development Environment:** Anaconda / Spyder
- **Dataset:** Heart Disease UCI Dataset

## Machine Learning Algorithm

### Random Forest Classifier

Random Forest is a supervised Machine Learning algorithm that uses multiple decision trees to make predictions.

In this project, the Random Forest Classifier analyzes different health parameters and classifies the input into:

- No Heart Disease
- Heart Disease Risk Detected

The final prediction is generated based on the combined results of multiple decision trees.

## Dataset Description

The project uses the Heart Disease UCI dataset.

The dataset contains medical attributes such as:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise-Induced Angina
- ST Depression
- Number of Major Vessels
- Thalassemia

The target variable indicates the presence or absence of heart disease.

## Project Workflow

1. Dataset Collection
2. Data Preprocessing
3. Handling Missing Values
4. Data Encoding
5. Training and Testing Data Splitting
6. Random Forest Model Training
7. Heart Disease Prediction
8. Model Evaluation

## Evaluation Metrics

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Classification Report

## Expected Output

The system accepts health-related input data and predicts the possibility of heart disease.

**Example:**

- Input: Patient health parameters
- Algorithm: Random Forest Classifier
- Output: Heart Disease Detected / No Heart Disease Detected

## Future Enhancements

- Integrate a user-friendly web application.
- Include additional disease prediction models.
- Improve prediction performance using larger datasets.
- Develop a patient health history dashboard.
- Add personalized health recommendations.

## Disclaimer

This project is developed for educational and academic purposes. Its predictions are not a substitute for professional medical diagnosis or treatment. Always consult a qualified healthcare professional for medical advice.
