# 🧪 Diabetes Classification using Naive Bayes

This project demonstrates a basic supervised machine learning pipeline to classify whether a patient has diabetes using the **Naive Bayes** algorithm. The dataset used is the Pima Indians Diabetes dataset, a well-known benchmark for binary classification tasks.

---

## 📁 Dataset

The dataset used in this project is available in the path:
/Dataset-main/Diabetes.csv


### 📊 Features:
- `pregnancies`: Number of times pregnant
- `glucose`: Plasma glucose concentration
- `diastolic`: Diastolic blood pressure (mm Hg)
- `triceps`: Triceps skin fold thickness (mm)
- `insulin`: 2-Hour serum insulin (mu U/ml)
- `bmi`: Body mass index (weight in kg/(height in m)^2)
- `dpf`: Diabetes pedigree function
- `age`: Age in years
- `diabetes`: Target (1 if diabetic, 0 otherwise)

---

## 🚀 Workflow

### 1. **Data Preprocessing**
- Load and explore the dataset
- Select relevant features
- Split the dataset into **training** and **testing** sets (70:30 split)
- Standardize features using `StandardScaler`

### 2. **Model Training**
- Use the `GaussianNB` (Naive Bayes) classifier from `scikit-learn`
- Fit the model to the training data

### 3. **Model Evaluation**
- Make predictions on the test set
- Evaluate using:
  - Confusion Matrix
  - Classification Report (Precision, Recall, F1-score)

---

## 🛠️ Libraries Used

- `pandas`
- `numpy`
- `scikit-learn`

---

## 📈 Results

After training and testing the model, performance is evaluated using classification metrics such as:

- Accuracy
- Precision
- Recall
- F1-Score

These metrics help assess the model's ability to correctly classify diabetic and non-diabetic patients.

---

## 🔍 How to Run

1. Unzip the dataset:
```
   !unzip "/content/drive/MyDrive/MASTER/Projects_and_datasets/Complete-classification-algos-of-Supervised-Learning--main.zip"
```
2. Run the complete pipeline:

Load data with pandas

Preprocess and scale features

Train the GaussianNB model

Evaluate the model

