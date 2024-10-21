# Spam Email Detection

**Task 3** of my **CognoRise Infotech Machine Learning Internship** focuses on developing a machine learning model to classify email messages as **spam** or **ham (not spam)**. The project utilizes a variety of machine learning algorithms to build and evaluate a classifier based on the content of email messages.

## Overview
This project uses a dataset containing email messages labeled as either **spam** or **ham**. The goal is to classify new email messages into these categories using different machine learning models:
- **Logistic Regression**
- **Random Forest Classifier**
- **AdaBoost Classifier**
- **K-Nearest Neighbors (KNN)**

The messages are transformed into numerical features using **TF-IDF Vectorization** before being passed to the models for classification.

## Project Steps

### 1. Data Cleaning:
- Checked for missing values and dropped irrelevant columns.

### 2. Data Preprocessing:
- Converted the `Category` column to numerical values where **spam = 1** and **ham = 0**.
- Vectorized the `Message` column using **TF-IDF** to convert the text data into numerical features.
  
### 3. Model Building:
Implemented the following classification models:
- **Logistic Regression**
- **Random Forest Classifier**
- **AdaBoost Classifier**
- **K-Nearest Neighbors (KNN)**

### 4. Model Evaluation:
Each model was evaluated based on:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**

### 5. New User Input for Spam Prediction:
The project allows users to input a new email message and get a prediction on whether it is **spam** or **ham** using the trained models.

## Results
Here are the accuracy scores for the models:
- **Logistic Regression**: 96%
- **Random Forest**: 98%
- **AdaBoost**: 98%
- **K-Nearest Neighbors**: 92%

The classification reports also provide detailed metrics such as **precision**, **recall**, and **F1-score** for both **spam** and **ham** categories.

## How to Use
1. Clone this repository to your local machine.
2. Open the `Spam_Email_Detection.ipynb` file in Jupyter Notebook or Google Colab.
3. Run the cells to train the models and test them.
4. Input new email messages in the provided section to predict whether they are **spam** or **ham**.

## Dataset
The dataset used in this project contains two columns:
- **Category**: Label of the email (spam or ham).
- **Message**: The content of the email.

You can replace the dataset with your own email data for further testing and customization.

## Requirements
Install the following libraries to run the project:
- `pandas`
- `numpy`
- `scikit-learn`

You can install them using pip:
```bash
pip install pandas numpy scikit-learn
```

## License
This project is licensed under the MIT License - see the LICENSE file for details.
