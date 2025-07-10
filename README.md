# ML Lab 3 – Diabetes Prediction Using Linear Regression

This repository contains the implementation of a basic machine learning model to predict diabetes outcomes using the Pima Indians Diabetes dataset.

## 📁 Files

- `ML-LAB-3.ipynb`: Jupyter notebook (Google Colab compatible) for data preprocessing, model training, and evaluation.
- `diabetes.csv`: Dataset used for the model (loaded from Google Drive or local path).
- `README.md`: Project overview and instructions.

## 📊 Project Overview

The goal of this lab is to predict whether a patient has diabetes based on medical attributes such as glucose level, BMI, insulin level, etc., using a **Linear Regression** model.

Although Linear Regression is not typically used for classification tasks, it's applied here for educational purposes. The predicted continuous values are rounded to classify outcomes (0 = No Diabetes, 1 = Diabetes).

## ⚙️ Steps Performed

1. **Load Dataset**
2. **Handle Missing Values**
   - Replace zeroes in critical fields with the mean.
3. **Feature Selection**
   - Selected features include `Glucose`, `BMI`, `Age`, etc.
4. **Train/Test Split**
5. **Train Model**
   - Using `LinearRegression` from `scikit-learn`
6. **Evaluate Model**
   - Accuracy, Confusion Matrix, Precision, Recall, F1 Score

## 📈 Model Evaluation (Sample Output)

Accuracy: 0.77
Precision: 0.74
Recall: 0.69
F1 Score: 0.71

> *Note: Actual results may vary slightly depending on the dataset and random state.*

## 📂 How to Run

1. Open `ML-LAB-3.ipynb` in **Google Colab** or **Jupyter Notebook**.
2. Make sure the dataset (`diabetes.csv`) is accessible:
   - Option 1: Upload it to your Google Drive in the path: `MyDrive/ML Lab/diabetes.csv`
   - Option 2: Modify the code to load from local file if running offline.
3. Run the notebook cells step-by-step.

## ✅ Requirements

- Python 3.x
- Libraries:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - Google Colab (for Drive access)

## 🔗 Dataset Source

Pima Indians Diabetes Dataset: [Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)

## 👨‍💻 Author

- **Name**: Shourov  
- **Institute**: Green University of Bangladesh  
- **Course**: Machine Learning Lab

## 📜 License

This project is for academic and educational use.
