````md
# 🚢 Titanic Survival Prediction (Machine Learning Project)

## Overview
This project is a machine learning classification model built to predict passenger survival on the Titanic based on features such as age, gender, passenger class, and other attributes.

The goal is to demonstrate an end-to-end machine learning workflow including data preprocessing, feature engineering, model training, evaluation, and hyperparameter tuning.

---

## Dataset
The dataset used is the Titanic dataset (commonly used for classification tasks).

- Training data: `train.csv`
- Test data: `test.csv`

---

## Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Machine Learning Workflow
1. Data loading and exploration
2. Data cleaning and handling missing values
3. Feature engineering
4. Encoding categorical variables
5. Model training and comparison
6. Hyperparameter tuning
7. Model evaluation

---

## Models Used
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Random Forest

---

## Model Performance

The following models were evaluated:

- Logistic Regression: 81.56%
- K-Nearest Neighbors (KNN): 72.62%
- Random Forest: 82.12%

---

## Hyperparameter Tuning

RandomizedSearchCV was applied to both Logistic Regression and Random Forest models.

GridSearchCV was also applied to Logistic Regression.

After tuning, Logistic Regression was selected as the best performing model since it achieved the best and most stable performance.

Final selected model accuracy:
- Logistic Regression: 81.56%

---

## How to Run This Project

### 1. Clone the repository
```bash
git clone https://github.com/Gfocus10/titanic-classification.git
cd titanic-classification
````

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the notebook

```bash
jupyter notebook
```

Open:
`titanic_model.ipynb`

---

## Project Structure

```
titanic-classification/
│
├── notebooks/
│   └── titanic_model.ipynb
├── data/
│   ├── train.csv
│   └── test.csv
├── requirements.txt
└── README.md
```

---

## Author

Jubril Adekunle

```
```
