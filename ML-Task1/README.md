# Breast Cancer Classification

**Task 1** of my **CognoRise Infotech Machine Learning Internship** focuses on developing a machine learning model to classify breast cancer tumors as **malignant** or **benign** using features extracted from mammogram data.

## Overview
This project uses the **Breast Cancer Wisconsin Dataset** to classify tumors as either malignant or benign based on features such as **radius**, **texture**, **perimeter**, and **smoothness**. Several machine learning models are implemented to perform this classification, including:
- **K-Nearest Neighbors (KNN)**
- **Random Forest Classifier**
- **Logistic Regression**
- **Decision Tree Classifier**
- **Linear Regression**

The dataset consists of multiple features related to the characteristics of the cell nuclei present in a digitized image of a breast mass.

## Project Steps

### 1. Data Cleaning and Preprocessing:
- Dropped irrelevant columns and checked for missing values.
- Encoded the **diagnosis** column where **M (Malignant) = 1** and **B (Benign) = 0**.
- Scaled the feature values for better model performance.

### 2. Model Building:
Implemented the following machine learning models:
- **K-Nearest Neighbors (KNN)**
- **Random Forest Classifier**
- **Logistic Regression**
- **Decision Tree Classifier**
- **Linear Regression** (used here for comparison, though typically not for classification).

### 3. Model Evaluation:
The models were evaluated based on:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**

### 4. New User Input for Prediction:
The project allows users to input features manually and receive predictions (either **Malignant** or **Benign**) based on the trained models.

## Results
Here are the accuracy scores for the models:
- **KNN**: 94%
- **Random Forest**: 95%
- **Logistic Regression**: 95%
- **Decision Tree**: 93%
- **Linear Regression**: 93%

## How to Use
1. Clone this repository to your local machine.
2. Open the `Breast Cancer Classification.ipynb` file in Jupyter Notebook or Google Colab.
3. Run the cells to train the models and test them.
4. Input new data in the provided section to predict whether the tumor is malignant or benign.

## Dataset
The dataset used in this project is the **Breast Cancer Wisconsin Dataset**. You can find more information and download the dataset [here](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data).

## Requirements
Install the following libraries to run the project:
- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`

You can install them using pip:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## License
This project is licensed under the MIT License - see the LICENSE file for details.
