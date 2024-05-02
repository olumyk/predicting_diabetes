# Predicting Diabetes - Utilizing Data for Proactive Health Management

## Introduction
This repository contains the code and resources for my project on diabetes prediction. This project provides valuable insights into the prediction of diabetes using machine learning techniques. The project involved several steps including data loading, exploration, cleaning, analysis, model training, evaluation, and interpretation.

## Dataset
The dataset used in this project contains information related to diabetes, including various health indicators and patient data. 

## Project Steps
1. **Data Loading and Exploration**: I downloaded the dataset and stored it as a .csv file. Next, I imported the dataset into a Jupyter notebook for initial exploration, aiming to grasp its structure and characteristics. Additionally, I included the download link and reference in the Jupyter notebook.

2. **Data Cleaning**: After exploring the dataset, I cleaned the data by handling missing values, outliers, and other inconsistencies.

3. **Data Analysis**: I conducted in-depth analysis of the dataset to gain insights into the relationships between different features and the target variable (diabetes).

4. **Model Training**: Using machine learning algorithms, I trained several models for diabetes prediction. The algorithms used include Decision Trees (DT), Random Forest (RF), Gradient Boosting (GB), XGBoost (XGB), CatBoost (CatB), LightGBM (LGBM), and AdaBoost (AB).

5. **Cross Validation**: I performed cross-validation using stratified k-fold technique to evaluate the performance of each model and ensure robustness.

6. **Pipeline Creation**: For preprocessing, I created a pipeline that included SMOTEENN for handling class imbalance and StandardScaler for feature scaling.

7. **Model Selection and Retraining**: Based on cross-validation results, I selected the best performing model and retrained it using the full training set.

8. **Prediction**: Finally, I used the trained model to make predictions on new data.

9. **Model Interpretation**: To interpret the model and understand its decision-making process, I utilized SHAP and LIME methods.

## Usage
To reproduce the results of this project, follow these steps:
1. Clone this repository to your local machine.
2. Install the necessary dependencies as specified in the library section.
3. Open the Jupyter Notebook file (`diabetes.ipynb`) and execute each cell sequentially.

## Conclusion
This capstone project provided valuable insights into the prediction of diabetes using machine learning techniques. By following the outlined steps, one can understand the process of building and evaluating predictive models for medical diagnosis.

For any questions or further information, feel free to contact me.

Thank you for visiting this repository!


Mayokun Ajiboye
