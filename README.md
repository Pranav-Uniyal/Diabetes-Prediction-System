#  Diabetes Prediction System

A machine learning-based system for predicting the likelihood of diabetes in individuals based on health parameters. Built using Python, Jupyter Notebook, and Scikit-learn, this project leverages Support Vector Machines (SVM) for accurate prediction and includes preprocessing, model training, and prediction pipelines.

---

## 📂 Project Structure
```
├── Diabetes_Prediction.ipynb # Jupyter Notebook containing full code
├── diabetes.csv # Dataset used for training and testing
├── diabetes_model.pkl # Trained ML model (SVM)
├── diabetes_scaler.pkl # StandardScaler object for input normalization
└── README.md # Project documentation
```

---

## Dataset

- Source: [Pima Indians Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- Features include:
  - Pregnancies
  - Glucose
  - BloodPressure
  - SkinThickness
  - Insulin
  - BMI
  - DiabetesPedigreeFunction
  - Age
- Target: `Outcome` (1 indicates diabetes, 0 indicates no diabetes)

---

##  Model Details

- **Algorithm**: Support Vector Machine (SVM)
- **Scaler Used**: `StandardScaler` for feature normalization
- **Evaluation Metrics**: Accuracy

---

##  How to Run

## 1. Clone the Repository

```bash
git clone https://github.com/Pranav-Uniyal/Diabetes-Prediction-System.git
cd Diabetes-Prediction-System
```
## 2. Install Required Packages
```
pip install scikit-learn pandas numpy matplotlib jupyter
```
## 3. Launch the Notebook
```
jupyter notebook Diabetes_Prediction.ipynb
```
---
## Pranav Uniyal
