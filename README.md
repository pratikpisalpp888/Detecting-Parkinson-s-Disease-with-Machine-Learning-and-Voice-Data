## Parkinson’s Disease Detection using Voice Data

This project focuses on detecting Parkinson’s disease using machine learning techniques applied to voice data. Since Parkinson’s affects speech, voice measurements can help in early detection.

The goal is to build a model that can classify whether a person is healthy or has Parkinson’s disease based on vocal features.

## Dataset:The dataset contains multiple biomedical voice measurements such as:
Fundamental frequency
Jitter and shimmer
Noise-to-harmonics ratio
Other vocal parameters

These features are used as inputs to train the model.

## Approach

The overall workflow of the project includes:

Data loading and basic exploration
Data preprocessing and cleaning
Feature selection
Splitting data into training and testing sets
Training machine learning models
Evaluating model performance

## Model

Different classification algorithms can be applied to this problem.
The model is trained to classify:

1 → Parkinson’s disease detected
0 → Healthy

##  Tech Stack
Python
NumPy
Pandas
Scikit-learn-SVC

## How to Run
Clone the repository
Open the notebook
Run all cells
Use the test input section to give new values

##Example:

### data = (your feature values here)

The model will output whether the person is healthy or has Parkinson’s disease.

## Results

The model is able to classify individuals based on voice features with good accuracy, showing the potential of machine learning in early-stage disease detection.

## Key Learnings
Working with real-world healthcare data
Importance of preprocessing and feature selection
Training and evaluating classification models
Making predictions on unseen data

## Future Improvements
Experiment with advanced models and tuning
Improve accuracy and evaluation metrics
Deploy as a web application (e.g., Streamlit)

## Conclusion

This project demonstrates how machine learning can be applied to healthcare problems in a simple and effective way. Voice-based detection can act as a non-invasive and quick method for early diagnosis.
