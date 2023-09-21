# EEG-based ADHD Classification

This project is focused on the classification of ADHD using raw EEG input. The raw EEG input undergoes filtering through a Butterworth filter, followed by the application of Independent Component Analysis (ICA). The classification of ADHD is then executed using the LightGBM model, providing insightful results in understanding and detecting ADHD patterns from EEG data.

## Overview
This project demonstrates the feasibility and accuracy of using machine learning models, specifically LightGBM, in classifying ADHD based on processed EEG data, contributing significantly to the field of medical diagnosis and mental health assessment.

## Structure
1. **Raw EEG Input Processing**: Initial stage involves acquiring and processing raw EEG data.
2. **Filtering with Butterworth Filter**: The processed EEG data is then filtered using a Butterworth filter to isolate relevant features.
3. **Application of ICA**: Independent Component Analysis (ICA) is applied to the filtered data to separate independent sources.
4. **ADHD Classification with LightGBM**: The final step involves the classification of ADHD using the LightGBM model, assessing the patterns in the EEG data.

## Results
Using LightGBM for ADHD classification, we achieved an accuracy of \( \approx 90.95\% \). Here are the scores from different models used:
- **KNN**: \( \approx 94.76\% \)
- **LightGBM**: \( \approx 90.95\% \)
- **Logistic Regression**: \( \approx 42.86\% \)
- **MLPClassifier**: \( \approx 42.86\% \)
- **Random Forest**: \( \approx 42.86\% \)

## Usage
To run the code in your local Jupyter Notebook, clone the repository and open the `.ipynb` file. Ensure that you have all the required libraries installed.

## contact datasci888@gmail.com 

