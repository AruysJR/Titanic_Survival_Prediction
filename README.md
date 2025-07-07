# Titanic - Machine Learning from Disaster

Note: This project is a Kaggle competition solution that predicts which passengers survived the Titanic disaster.

## Files
- `titanic_model_rf.ipynb` – Main notebook with EDA, preprocessing, feature engineering, modeling, and prediction.
- `train.csv` – Training dataset used to build and evaluate the model.
- `test.csv` – Test dataset used for final predictions.
- `submission.csv` – Final output file submitted to Kaggle, containing `PassengerId` and `Survived`.

## What Was Done in the Project
- Performed exploratory data analysis (EDA) to understand the dataset.
- Handled missing values.
- Extracted and mapped titles from names to make the data more meaningful.
- Created new features like `FamilySize` and `Has_Cabin`.
- Applied one-hot encoding to categorical variables and avoided the dummy variable trap.
- Trained a model using **Random Forest**.
- Prepared the `submission.csv` file using the `PassengerId` from the original test file and the model’s predictions.

## Dataset Source
Datasets were sourced from the [Titanic competition on Kaggle](https://www.kaggle.com/competitions/titanic/data).
