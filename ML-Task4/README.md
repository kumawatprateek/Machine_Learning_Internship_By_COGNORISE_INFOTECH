# Sentiment Analysis on Movie Reviews

**Task 4** of my **CognoRise Infotech Machine Learning Internship** focuses on building a **sentiment analysis** system to classify movie reviews as either **positive** or **negative**. The project implements several machine learning models to perform this classification task.

## Overview
This project uses a dataset of movie reviews from the **IMDB** dataset to predict the sentiment of each review. Various machine learning models are applied to classify the sentiment as either **positive** or **negative** based on the review text. The models used include:
- **Naive Bayes Classifier**
- **Random Forest Classifier**
- **K-Nearest Neighbors (KNN)**
- **XGBoost Classifier**
- **Logistic Regression**
- **Decision Tree Classifier**

The review text is vectorized using **TF-IDF** for converting text data into numerical features suitable for modeling.

## Project Steps

### 1. Data Cleaning:
- Removed any missing values from the dataset.

### 2. Data Preprocessing:
- Converted the `sentiment` column to binary values where **positive = 1** and **negative = 0**.
- Vectorized the `review` column using **TF-IDF** to extract the most important features from the text data.

### 3. Model Building:
Implemented the following classification models:
- **Naive Bayes Classifier**
- **Random Forest Classifier**
- **K-Nearest Neighbors (KNN)**
- **XGBoost Classifier**
- **Logistic Regression**
- **Decision Tree Classifier**

### 4. Model Evaluation:
Each model was evaluated based on:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**

### Results:
The **accuracy** scores for each model are:
- **Naive Bayes**: 85%
- **Random Forest**: 86%
- **K-Nearest Neighbors**: 73%
- **XGBoost**: 86%
- **Logistic Regression**: 89%
- **Decision Tree**: 72%

The models were further evaluated using detailed metrics such as **precision**, **recall**, and **F1-score**.

## How to Use
1. Clone this repository to your local machine.
2. Open the `Sentiment_Analysis_on_Movie_Reviews.ipynb` file in Jupyter Notebook or Google Colab.
3. Run the cells to train and test the models.
4. Modify the notebook to input your own movie reviews for sentiment classification.

## Dataset
The dataset used in this project is the **IMDB Movie Reviews Dataset**. The data contains two columns:
- **review**: The text of the movie review.
- **sentiment**: The sentiment label, either **positive** or **negative**.

You can replace the dataset with your own movie review data to extend the project.

## Requirements
Install the following libraries to run the project:
- `pandas`
- `numpy`
- `scikit-learn`
- `xgboost`

You can install them using pip:
```bash
pip install pandas numpy scikit-learn xgboost
```

## License
This project is licensed under the MIT License - see the LICENSE file for details.
