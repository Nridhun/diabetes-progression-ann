

# Diabetes Progression Prediction using ANN

## Project Overview

This project uses an Artificial Neural Network (ANN) to predict diabetes progression using the Diabetes dataset available in the sklearn library.

## Steps Performed

- Loaded the Diabetes dataset
- Checked for missing values
- Performed Exploratory Data Analysis (EDA)
- Normalized the features using StandardScaler
- Split the data into training and testing sets
- Built an Artificial Neural Network
- Trained and evaluated the model
- Improved the model by changing the architecture
- Compared the performance of two ANN models

## Model Performance

| Model | Test MSE | Test MAE | R² Score |
|---|---:|---:|---:|
| Model 1 | 2890.48 | 43.51 | 0.4544 |
| Model 2 | 2857.34 | 42.38 | 0.4607 |

## Conclusion

Model 2 performed slightly better than Model 1. It achieved an R² score of 0.4607, showing that the ANN was able to learn the relationship between the features and diabetes progression.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow / Keras
- Jupyter Notebook
