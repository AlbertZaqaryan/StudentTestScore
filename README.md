# Student Test Score Prediction

Machine Learning project for predicting student test scores using demographic, academic, and lifestyle-related features. This project was created as part of the Kaggle competition: [Playground Series S6E1](https://www.kaggle.com/competitions/playground-series-s6e1?utm_source=chatgpt.com)

Repository: [StudentTestScore GitHub Repo](https://github.com/AlbertZaqaryan/StudentTestScore?utm_source=chatgpt.com)

---

## Overview

This project focuses on building and evaluating machine learning models to predict student exam performance.
The workflow includes:

* Data preprocessing
* Exploratory Data Analysis (EDA)
* Feature engineering
* Model training
* Hyperparameter tuning
* Model evaluation
* Kaggle submission generation

The goal is to achieve the best prediction accuracy on unseen student data.

---

## Dataset

Competition Dataset:
[Kaggle Playground Series S6E1 Dataset](https://www.kaggle.com/competitions/playground-series-s6e1/data?utm_source=chatgpt.com)

The dataset contains various student-related attributes such as:

* Gender
* Study time
* Parental education
* Internet access
* Attendance
* Previous scores
* Lifestyle factors
* Other academic indicators

Target variable:

* Student test score prediction

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* LightGBM
* CatBoost
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Project Structure

```bash
StudentTestScore/
│
├── data/                 # Dataset files
├── notebooks/            # Jupyter notebooks
├── models/               # Saved trained models
├── submissions/          # Kaggle submission files
├── requirements.txt
├── README.md
└── main.ipynb
```

---

## Machine Learning Pipeline

### 1. Data Preprocessing

* Missing value handling
* Encoding categorical features
* Feature scaling
* Outlier analysis

### 2. Exploratory Data Analysis

* Correlation analysis
* Distribution visualization
* Feature importance investigation

### 3. Model Training

Implemented multiple regression/classification models including:

* Logistic Regression
* Random Forest
* XGBoost
* LightGBM
* CatBoost

### 4. Hyperparameter Tuning

Used:

* GridSearchCV
* Cross-validation
* Pipeline optimization

Example:

```python
params = {
    'model__n_estimators': [100, 200],
    'model__max_depth': [3, 5, 7]
}
```

### 5. Evaluation Metrics

* Accuracy
* RMSE
* MAE
* Cross-validation score

---

## Installation

Clone the repository:

```bash
git clone https://github.com/AlbertZaqaryan/StudentTestScore.git
```

Move into the project directory:

```bash
cd StudentTestScore
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Running the Project

Open Jupyter Notebook:

```bash
jupyter notebook
```

Run:

```bash
main.ipynb
```

---

## Kaggle Competition

Competition link:
[Kaggle Playground Series S6E1](https://www.kaggle.com/competitions/playground-series-s6e1?utm_source=chatgpt.com)

This competition is part of Kaggle’s Playground Series designed for practicing machine learning and feature engineering techniques. ([GitHub][1])

---

## Results

* Built multiple ML pipelines
* Compared several ensemble models
* Improved validation performance using hyperparameter tuning
* Generated Kaggle-ready prediction submissions

---

## Future Improvements

* Advanced feature engineering
* Ensemble stacking/blending
* Deep learning experiments
* Automated ML pipelines
* SHAP explainability analysis

---

## Author

Created by [Albert Zaqaryan GitHub](https://github.com/AlbertZaqaryan?utm_source=chatgpt.com)

If you like this project, feel free to star the repository ⭐

[1]: https://github.com/NadavKiani/Students-Performance-in-Exams?utm_source=chatgpt.com "GitHub - NadavKiani/Students-Performance-in-Exams"
