# Heart-Disease-Classification
This is an end-to-end classic machine learning project of heart disease classification leveraging heart disease dataset from UCI Machine Learning Repository.

# Predicting Heart Disease using Machine Learning 

This project use various python-based machine learning and data science libraries in an attempt to build a machine learning model capable of predicting whether or not someone has heart disease or not based on their medical attributes.

We're going to take the following approach:
1. Problem Definition
2. Data
3. Evaluation
4. Features
5. Modelling
6. Experimentation

## 1.Problem Definition
>Can you predict whether the patient has heart disease or not based on the given clinical parameter.
## 2.Data
The original data came from Cleveland, Hungary, Switzerland, and the VA Long Beach and is available on UCI Machine Learning Repository.
https://archive.ics.uci.edu/dataset/45/heart+disease
## 3.Evaluation 
> If we can reach 95% Accuracy to predict the heart disease.
## 4.Features 
This is where you get different information about each of the feature in your data. 
**Create Data Dictionary** 

| Feature  | Description | Example Values |
|:-----|:-----|:------|
| **age** | Age in years | 29, 45, 60 |
| **sex** | 1 = male; 0 = female | 0, 1  |
| **cp**  | Chest pain type | 0: Typical angina (chest pain), 1: Atypical angina (chest pain not related to heart), 2: Non-anginal pain (typically esophageal spasms (non heart related), 3: Asymptomatic (chest pain not showing signs of disease) |
| **trestbps** | Resting blood pressure (in mm Hg on admission to the hospital)  | 120, 140, 150 |
| **chol** | Serum cholesterol in mg/dl | 180, 220, 250 |
| **fbs** | Fasting blood sugar > 120 mg/dl (1 = true; 0 = false) | 0, 1 |
| **restecg** | Resting electrocardiographic results | 0: Nothing to note, 1: ST-T Wave abnormality, 2: Left ventricular hypertrophy  |
| **thalach** | Maximum heart rate achieved | 160, 180, 190 |
| **exang**  | Exercise induced angina (1 = yes; 0 = no) | 0, 1 |
| **oldpeak**  | ST depression (heart potentially not getting enough oxygen) induced by exercise relative to rest | 0.5, 1.0, 2.0  |
| **slope** | The slope of the peak exercise ST segment | 0: Upsloping, 1: Flatsloping, 2: Downsloping |
| **ca** | Number of major vessels (0-3) colored by fluoroscopy | 0, 1, 2, 3 |
| **thal** | Thalium stress result  | 1: Normal, 3: Normal, 6: Fixed defect, 7: Reversible defect |
| **target** | Have disease or not (1 = yes; 0 = no) | 0, 1 |

# The End-to-End Classification Project is inside this notebook: https://github.com/mroshan454/Heart-Disease-Classification/blob/main/End-to-End-Heart-Disease-Classification.ipynb

