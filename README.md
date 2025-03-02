# [Horse Health Outcome Prediction](https://www.kaggle.com/code/hassaneskikri/horse-health-prediction)

![](https://feedsnneeds.ca/wp/wp-content/uploads/2020/12/Maintaining-your-horses-health.png)
## Project Overview
This project focuses on predicting health outcomes in horses using various machine learning models. The challenge is based on the Kaggle competition "Playground Series S3E22", which aims to develop accurate predictive models for horse health conditions.

## Problem Description
The goal is to predict horse health outcomes based on various medical and physical attributes. This is a binary classification problem where we predict whether a horse will survive or not based on the given features.

## Models Evaluated
We tested multiple classification models from scikit-learn and LightGBM:
- Gradient Boosting Classifier
- Random Forest Classifier
- Extra Trees Classifier
- AdaBoost Classifier
- LightGBM Classifier
- Ridge Classifier
- Logistic Regression
- Linear Discriminant Analysis
- Support Vector Classifier (SVC)

## Best Performing Model
After comprehensive cross-validation, the **Gradient Boosting Classifier** achieved the best performance with an accuracy of **73.01%**.

## Model Selection Process
- Implemented cross-validation to ensure robust model evaluation
- Compared multiple models using the same validation strategy
- Selected the best performing model based on accuracy metrics

## Project Structure
```
├── data/
│   ├── train.csv
│   └── test.csv
├── requirements.txt/
├── runtime.txt/
├── notebooks/
│   └── horse-health-prediction.ipynb
└── README.md
```

## Requirements
```
numpy
pandas
seaborn
matplotlib
scikit-learn
lightgbm
```

## Usage
1. Install the required packages:
```bash
pip install -r requirements.txt
```

## Future Improvements
- Feature engineering to create more informative predictors
- Hyperparameter optimization for the Gradient Boosting Classifier
- Ensemble methods combining multiple models
- Deep learning approaches if more data becomes available

## License
This project is licensed under the MIT License - see the LICENSE file for details.
