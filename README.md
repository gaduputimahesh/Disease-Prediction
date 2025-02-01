# Diabetes  disease Prediction 

Smart Healthcare Assistant for Disease Prediction and Management
Using Diabetes Dataset for Predictive Analytics


![images](https://github.com/user-attachments/assets/02192c32-02af-495c-b74b-8229a20e3cee) ![Image (1)](https://github.com/user-attachments/assets/db257086-c3c8-459b-8b1e-68275cd08530)



## Overview

This project aims to predict the risk of diabetes using machine learning techniques. It utilizes a dataset containing various health metrics such as glucose levels, BMI, blood pressure, age, and insulin levels. The system helps healthcare professionals in early detection and prevention of diabetes.

## Features

- Data preprocessing and feature scaling
- Exploratory Data Analysis (EDA) with visualizations
- Machine Learning Model training and evaluation
- Predictive analysis for diabetes risk assessment

## Dataset

The dataset used in this project is `diabetes_prediction_dataset.csv`, which includes the following columns:

- **Pregnancies**: Number of times pregnant
- **Glucose**: Plasma glucose concentration
- **BloodPressure**: Diastolic blood pressure (mm Hg)
- **SkinThickness**: Triceps skin fold thickness (mm)
- **Insulin**: 2-Hour serum insulin (mu U/ml)
- **BMI**: Body mass index (weight in kg/(height in m)^2)
- **DiabetesPedigreeFunction**: A function which scores likelihood of diabetes
- **Age**: Age of the person
- **Outcome**: Diabetes diagnosis (1 = Positive, 0 = Negative)

## Data Processing

- Handling missing values
- Feature scaling using StandardScaler
- Splitting data into training and testing sets

## Model Training

- Implemented multiple machine learning models including Logistic Regression, Random Forest, and Support Vector Machine (SVM)
- Hyperparameter tuning for optimal performance
- Model selection based on evaluation metrics

## Model Evaluation

- Accuracy, Precision, Recall, and F1-score calculations
- ROC Curve and AUC score for performance measurement
- Confusion Matrix visualization

## Visualizations

Below are some key visualizations generated during Exploratory Data Analysis:

### Data Distribution

![diabetes_plot_2](https://github.com/user-attachments/assets/3ad8681c-06e3-4064-ade5-a64780398333)



### Correlation Heatmap

![diabetes_plot_3](https://github.com/user-attachments/assets/01c45ad4-f4e0-4b42-8cfb-35a6c0b7e1b2)



### Pair Plots

![diabetes_plot_4 (1)](https://github.com/user-attachments/assets/cee7d5cc-49da-4ce4-a64d-48c28252ab42)


### Model Performance

![diabetes_plot_5](https://github.com/user-attachments/assets/621dede8-d77d-4014-83c9-43f9b8631f65)

![diabetes_plot_6](https://github.com/user-attachments/assets/17b1ca12-4bfc-4a54-9ec2-8286c76b259b)


## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/gaduputimahesh/diabetes-prediction.git
   ```
2. Navigate to the project directory:
   ```sh
   cd diabetes-prediction
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook:
   ```sh
   jupyter notebook diabetes-prediction.ipynb
   ```

## Results

The model achieved an accuracy of 75%. Various evaluation metrics such as precision, recall, and F1-score were used to assess performance.

## Contributions

Contributions are welcome! Feel free to fork the repository and submit pull requests.


Thank You
