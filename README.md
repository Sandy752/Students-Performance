![GitHub repo size](https://img.shields.io/github/repo-size/sumit0072/Car-Price-Prediction-Project?style=for-the-badge)
![GitHub language count](https://img.shields.io/github/languages/count/sumit0072/Car-Price-Prediction-Project?style=for-the-badge)
![GitHub top language](https://img.shields.io/github/languages/top/sumit0072/Car-Price-Prediction-Project?style=for-the-badge)
![GitHub last commit](https://img.shields.io/github/last-commit/sumit0072/Car-Price-Prediction-Project?color=red&style=for-the-badge)


# Students Performance Prediction

## Table of contents
* [Dataset Preview](#dataset-preview)
* [Demo](#demo)   
* [Tools Used](#3)
* [Libraries](#4)
* [Algorithms Used](#5)
* [Model Performance Summary](#model-performance-summary)
* [Installation](#installation)


## Dataset Preview

A preview of top five rows of the Students Performance dataset.

| gender | race_ethnicity | parental_level_of_education | lunch         | test_preparation_course | math_score | reading_score | writing_score |
|--------|----------------|-----------------------------|---------------|-------------------------|------------|---------------|---------------|
| female | group B       | bachelor's degree           | standard      | none                    | 72         | 72            | 74            |
| female | group C       | some college                | standard      | completed               | 69         | 90            | 88            |
| female | group B       | master's degree             | standard      | none                    | 90         | 95            | 93            |
| male   | group A       | associate's degree          | free/reduced   | none                    | 47         | 57            | 44            |
| male   | group C       | some college                | standard      | none                    | 76         | 78            | 75            |

## Demo

progress!!!!

<h3>Tools Used </h3><a id="3"></a>

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)

<h3>Libraries</h3><a id="4"></a>

![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-FF7F0E?style=for-the-badge&logo=matplotlib&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-30B5E3?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)


<h3>Algorithms Used<h3><a id="5"></a>

1. Decision Tree
2. Random Forest (yielding highest accuracy)
3. Linear Regression
4. Lasso
5. K-Neighbors Regressor
6. AdaBoost Regressor
7. Ridge
8. XGBRegressor

## Model Performance Summary

| Model                     | Training RMSE | Training MAE | Training R² | Test RMSE | Test MAE | Test R² |
|---------------------------|----------------|---------------|--------------|-----------|----------|----------|
| Linear Regression         | 5.3271         | 4.2694       | 0.8741       | 5.4186    | 4.2195   | 0.8793   |
| Lasso                     | 6.5938         | 5.2063       | 0.8071       | 6.5197    | 5.1579   | 0.8253   |
| Ridge                     | 5.3233         | 4.2650       | 0.8743       | 5.3904    | 4.2111   | 0.8806   |
| K-Neighbors Regressor     | 5.7077         | 4.5167       | 0.8555       | 7.2530    | 5.6210   | 0.7838   |
| Decision Tree             | 0.2795         | 0.0187       | 0.9997       | 8.0200    | 6.3200   | 0.7357   |
| Random Forest Regressor   | 2.3227         | 1.8397       | 0.9761       | 6.0109    | 4.6502   | 0.8515   |
| XGBRegressor              | 1.0073         | 0.6875       | 0.9955       | 6.4733    | 5.0577   | 0.8278   |
| AdaBoost Regressor       | 5.9123         | 4.8520       | 0.8450       | 6.1733    | 4.8413   | 0.8434   |

**Summary:**  
The model performance indicates that the Decision Tree and XGBRegressor performed exceptionally well on the training set, with R² scores close to 1. However, the K-Neighbors Regressor and AdaBoost Regressor showed relatively lower performance on the test set, suggesting potential overfitting.


## Installation

* Clone this repository and unzip it.

* create new  venv with python 3 and activate it .

* Install the required packages using

 ``` bash
pip install -r requirements.txt
```

* Execute the command:
``` bash
  python3 app.py
```

* Open ```http://127.0.0.1:5000/``` in your browser.