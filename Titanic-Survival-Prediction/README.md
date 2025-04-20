# Titanic Survival Prediction

## Project Overview

This project aims to build a machine learning model to predict whether a passenger survived the Titanic disaster, based on features like age, gender, ticket class, fare, cabin information, and more. The project uses the Titanic dataset and applies various data preprocessing steps, model training, and performance evaluation.

### Dataset

The dataset used is a version of the Titanic passenger data available on Kaggle. It contains several columns with information about passengers, including whether they survived the Titanic disaster or not.

### Task Objectives

- Develop a machine learning model to predict whether a passenger survived the Titanic disaster.
- Handle missing values, encode categorical variables, and normalize numerical data.
- Evaluate the performance of the model using accuracy, precision, recall, and F1 score.

## Project Structure

```plaintext
Titanic-Survival-Prediction/
├── data/
│   └── tested.csv                   # Titanic dataset (you can upload your dataset here)
├── notebooks/
│   └── Titanic_Survival_Prediction.ipynb # Your notebook with all the code
├── requirements.txt                 # Dependencies for the project (you can manually create it)
└── README.md                        # Project documentation (this file)
```

## Steps to Run the Project

### 1. Clone the repository to your local machine or open it in Google Colab.

To clone the repository, use the following command:
```bash
!git clone https://github.com/Rambanni2004/Titanic-Survival-Prediction.git

```
### 2. Install dependencies:

Use requirements.txt to install the necessary libraries. You can install them using the following command:

```bash
pip install -r requirements.txt

```

### 3. Run the Jupyter notebook:

Open the notebook Titanic_Survival_Prediction.ipynb in your preferred Jupyter environment (such as Google Colab or Jupyter Notebook).

Execute each cell in the notebook to go through the steps of data preprocessing, model training, and evaluation.

## Conclusion
This project demonstrates how to use machine learning to predict survival on the Titanic disaster based on passenger data. It includes all necessary steps for data preprocessing, model training, and evaluation. The model's performance is evaluated using common metrics like accuracy, precision, recall, and F1 score.
