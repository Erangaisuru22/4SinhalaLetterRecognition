# Sinhala Letter Recognition using Machine Learning

## Overview

This project recognizes Sinhala vowel letters using Machine Learning techniques. The system is trained to identify four Sinhala letters:

* අ (A)
* ඉ (I)
* උ (U)
* එ (E)

The objective is to classify handwritten or printed Sinhala characters based on image features.

## Dataset

The dataset contains images of Sinhala letters:

* අ
* ඉ
* උ
* එ

Images are preprocessed by resizing, grayscale conversion, and normalization before training.

## Machine Learning Algorithms

1. K-Nearest Neighbors (KNN)
2. Decision Tree
3. Random Forest
4. Support Vector Machine (SVM)

## Technologies Used

* Python
* Scikit-learn
* NumPy
* Pandas
* OpenCV
* Matplotlib

## Project Workflow

1. Collect Sinhala letter images
2. Preprocess images
3. Extract features
4. Split dataset into training and testing sets
5. Train machine learning models
6. Evaluate model accuracy
7. Predict Sinhala letters

## Results

The models were evaluated using classification accuracy and confusion matrices. Performance comparison was conducted to identify the best algorithm for Sinhala letter recognition.

## Future Improvements

* Add all Sinhala vowels and consonants.
* Use Convolutional Neural Networks (CNN).
* Develop a real-time Sinhala handwriting recognition application.
