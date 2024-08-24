# Disease Prediction from Symptoms
    This project is an automated system for predicting diseases based on user-input symptoms, using a Naive Bayes algorithm. 
    The goal is to provide an initial diagnosis to save time and reduce costs associated with traditional diagnostic methods.

# Problem Statement
    Traditional Diagnosis: Requires a patient to visit a doctor, undergo various medical tests, and wait for results—a time-consuming and often expensive process.
    Proposed Solution: An automated system that predicts probable diseases based on symptoms entered by the user, providing a preliminary diagnosis.
# How It Works
    Input: The user selects symptoms from a predefined list.
    Prediction: The system uses the Naive Bayes algorithm, specifically Multinomial Naive Bayes, to predict the most likely diseases based on the symptoms provided.
    Output: The system outputs the name of the disease with the highest probability.
# Dataset
    Training Data: Contains records of various diseases and their associated symptoms.
    Testing Data: Used to validate the accuracy of the model.
# Algorithm
    Naive Bayes: A probabilistic classifier that performs well with categorical data. It is chosen due to its effectiveness with large datasets and multiple symptoms.
