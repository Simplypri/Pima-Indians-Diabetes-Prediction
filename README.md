PIMA Diabetes Prediction using Artificial Neural Networks

This project implements an Artificial Neural Network (ANN) to predict diabetes risk using the PIMA Indians Diabetes dataset. The model learns nonlinear relationships between medical diagnostic features to classify whether a patient is likely to have diabetes.

The implementation demonstrates a complete deep learning pipeline including data preprocessing, feature scaling, neural network design, training, and evaluation using PyTorch.

**Project Overview**

Early prediction of diabetes helps support clinical decision-making and preventive healthcare. This project uses patient health indicators such as glucose level, BMI, insulin level, age, and blood pressure to build a binary classification model that predicts diabetes outcomes. The model applies deep learning techniques to structured healthcare data to capture complex feature interactions that traditional models may miss.

**Dataset**

The PIMA Diabetes dataset contains medical diagnostic measurements for female patients of Pima Indian heritage.

Features include:

Pregnancies

Glucose

Blood Pressure

Skin Thickness

Insulin

BMI

Diabetes Pedigree Function

Age

Target:

Outcome (0 = No Diabetes, 1 = Diabetes)

**Project Workflow**

1. Data loading and exploration

2. Handling missing values

3. Feature scaling and preprocessing

4. ANN architecture design

5. Model training and validation

6. Performance evaluation (accuracy, loss)

**Model Architecture**

The Artificial Neural Network consists of: Input layer (medical features), Fully connected hidden layers with nonlinear activation, Output layer with sigmoid activation for binary classification

**Technologies Used**

PyTorch — neural network implementation

Pandas — data handling

NumPy — numerical computation

Scikit-learn — preprocessing and evaluation

Matplotlib / Seaborn — visualization

**Results**

The model successfully learns patterns in patient health indicators to predict diabetes risk and demonstrates the effectiveness of deep learning for structured healthcare data.
