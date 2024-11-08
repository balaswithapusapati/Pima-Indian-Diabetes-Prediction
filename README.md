# Diabetes Prediction Using Logistic Regression

## Project Overview
This project involves building a machine learning model to predict whether a patient has diabetes based on diagnostic measurements. The dataset used for this project is the **Pima Indians Diabetes Database**, sourced from Kaggle.

## Dataset
- **Source**: [Pima Indians Diabetes Database on Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database/data)
- **Context**: The dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. It includes data from females of at least 21 years of age of Pima Indian heritage.
- **Features**:
  - `Pregnancies`: Number of times pregnant
  - `Glucose`: Plasma glucose concentration
  - `BloodPressure`: Diastolic blood pressure (mm Hg)
  - `SkinThickness`: Triceps skinfold thickness (mm)
  - `Insulin`: 2-Hour serum insulin (mu U/ml)
  - `BMI`: Body mass index (weight in kg/(height in m)^2)
  - `DiabetesPedigreeFunction`: Diabetes pedigree function
  - `Age`: Age in years
- **Target Variable**:
  - `Outcome`: 1 indicates diabetic, 0 indicates non-diabetic

## Model
The model used in this project is **Logistic Regression**, which is suitable for binary classification problems.

## Steps to Run the Code
1. Clone the repository or download the project files.
2. Ensure the dataset is in the working directory or download it from [Kaggle](https://www.kaggle.com/uciml/pima-indians-diabetes-database).
3. Install the necessary Python packages:
   ```bash
   pip install numpy pandas scikit-learn matplotlib seaborn
   ```
4. Run the code using Jupyter Notebook, Google Colab, or any Python IDE.
   
## Code Overview
   
* Data Preprocessing:
Replaced zero values in Glucose, BloodPressure, SkinThickness, Insulin, and BMI with NaN and imputed them with the median.

* Feature Scaling:
Applied StandardScaler for scaling features.

* Model Training:
Trained a Logistic Regression model with a 70-30 train-test split.

* Evaluation:
Achieved an accuracy of 0.74025 and printed the confusion matrix and classification report for further analysis.

## Results
* Accuracy: 0.74025
* Evaluation Metrics:
Confusion Matrix and Classification Report were generated for a detailed evaluation of the model's performance.
