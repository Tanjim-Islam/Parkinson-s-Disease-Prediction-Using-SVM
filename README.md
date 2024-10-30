# Parkinson's Disease Prediction Using SVM

## Project Overview

This project focuses on predicting whether a person has Parkinson's disease using a Support Vector Machine (SVM) with a linear kernel. The goal is to accurately classify individuals as either healthy or affected by Parkinson's disease based on various biomedical measurements.

## Features

- **Binary Classification**: Classifies individuals as either **Healthy (0)** or **Parkinson's Disease (1)**.
- **Data Preprocessing**: Standardizes the feature set for consistent scaling.
- **Machine Learning Model**: Uses **Support Vector Machine (SVM)** with a linear kernel.
- **Prediction Example**: Predicts the health status of a patient using a sample input.

## Requirements

- **Python 3.10**
- **Pandas**
- **NumPy**
- **Scikit-learn**

## Installation

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/Tanjim-Islam/Parkinson-s-Disease-Prediction-Using-SVM.git
    ```

2. **Install Dependencies:**

    ```bash
    pip install pandas numpy scikit-learn
    ```

3. **Ensure the Dataset is Available:**
   Place `dataset.csv` in the working directory.

## Code Structure

1. **Data Preprocessing:**
   - Drops irrelevant columns (e.g., `name`).
   - Standardizes the feature set using `StandardScaler`.

2. **Model Training and Evaluation:**
   - Splits data into training and testing sets (80%/20%).
   - Trains an SVM with a linear kernel.
   - Evaluates the model with training and testing accuracy.

3. **Example Prediction:**
   - Uses the trained model to predict if a person has Parkinson's disease.

## Results

### Model Accuracy:

- **Training Accuracy**: 87.18%
- **Testing Accuracy**: 87.18%