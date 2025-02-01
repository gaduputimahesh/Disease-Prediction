# *Diabetes Prediction Pro*ject

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




### Correlation Heatmap



### Pair Plots



### Model Performance




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

The model achieved an accuracy of **X%** (replace with actual value). Various evaluation metrics such as precision, recall, and F1-score were used to assess performance.

## Contributions

Contributions are welcome! Feel free to fork the repository and submit pull requests.

## License

This project is open-source and available under the [MIT License](LICENSE).

