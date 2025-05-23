# Health & Flower Prediction Models

This repository contains three machine learning projects:

1. **Heart Disease Prediction** using Random Forest Classifier
2. **Diabetes Prediction** using Random Forest Classifier
3. **Iris Flower Classification** using K-Nearest Neighbors (KNN)

Each model is trained using publicly available datasets and implements standard machine learning workflows including data preprocessing, model training, evaluation, and prediction.

---

## 🔬 Project Details

### 1. Heart Disease Prediction (Framingham Study)

- **Model Used:** Random Forest Classifier
- **Dataset:** Framingham Heart Study Dataset
- **Features:**
  - `male`: Binary (1 = male, 0 = female)
  - `age`: Age of the patient (years)
  - `education`: Education level (categorical)
  - `currentSmoker`: Binary (1 = current smoker, 0 = non-smoker)
  - `cigsPerDay`: Number of cigarettes smoked per day
  - `BPMeds`: Binary (1 = patient was on blood pressure medication)
  - `prevalentStroke`: Binary (1 = patient had previously had a stroke)
  - `prevalentHyp`: Binary (1 = patient was hypertensive)
  - `diabetes`: Binary (1 = diabetic)
  - `totChol`: Total cholesterol level (mg/dL)
  - `sysBP`: Systolic blood pressure (mmHg)
  - `diaBP`: Diastolic blood pressure (mmHg)
  - `BMI`: Body Mass Index
  - `heartRate`: Heart rate (beats per minute)
  - `glucose`: Glucose level (mg/dL)
- **Target:**
  - `TenYearCHD`: Binary (1 = 10-year risk of coronary heart disease)
- **Accuracy:** 0.851
- **Libraries:** `pandas`, `numpy`, `sklearn`, `matplotlib`, `seaborn`


### 2. Diabetes Prediction

- **Model Used:** Random Forest Classifier
- **Dataset:** Pima Indians Diabetes Dataset
- **Features:** Pregnancies, Glucose, Blood Pressure, Skin Thickness, Insulin, BMI, Diabetes Pedigree Function, Age.
- **Target:** Diabetes (binary classification)
- **Accuracy:**0.792
- **Libraries:** `pandas`, `numpy`, `sklearn`, `matplotlib`, `seaborn`

## 🛠️ How to Run

1. Clone the repository:
