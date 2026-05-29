<<<<<<< HEAD
# Heart Disease Prediction

## Overview

This project predicts whether a patient is likely to have heart disease using Machine Learning techniques.

## Features

- Data preprocessing
- Feature scaling
- KNN classification
- Model deployment using Flask
- Interactive prediction interface

## Dataset

The dataset contains patient health information such as:

- Age
- Sex
- Chest Pain Type
- Blood Pressure
- Cholesterol
- Maximum Heart Rate
- Exercise Induced Angina

## Project Structure

```text
Heart-Disease-Prediction/
│
├── app.py
├── heart.csv
├── heart_columns.pkl
├── heart_scaler.pkl
├── knn_heart_model.pkl
├── HeartdiseaseFinal.ipynb
├── requirements.txt
└── README.md
```
## Results

Several machine learning models were evaluated:

| Model | Accuracy | F1 Score |
|---------|---------|---------|
| Logistic Regression | 87.5% | 0.8878 |
| KNN | 88.59% | 0.8986 |
| Naive Bayes | 86.96% | 0.8788 |
| Decision Tree | 76.09% | 0.7755 |
| SVM (RBF Kernel) | 86.41% | 0.8804 |

The KNN classifier achieved the best performance with an accuracy of **88.59%** and an F1-score of **0.8986**.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Flask

## How to Run

```bash
pip install -r requirements.txt
python app.py
```

## Author

Adhyan Kumar  
B.Tech AI & Data Science  
IIT Patna
=======
# Heart-Disease-Prediction
Machine Learning project for predicting heart disease using patient health parameters.
>>>>>>> 56de47a7bc5bc80d135c522fc60f7a8e94923b31
