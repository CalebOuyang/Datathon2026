# CMU Data Science Club Datathon 2026

## Project Overview
This project was developed for the CMU Data Science Club Datathon 2026. It implements an end-to-end data science workflow focused on unsupervised anomaly detection. The objective is to identify unusual or high-risk observations in the dataset using transparent, interpretable modeling techniques.

## Methodology
The notebook follows a standard data science pipeline:
- Data loading and inspection  
- Data preprocessing, including handling missing values, encoding categorical variables, and feature scaling  
- Exploratory data analysis to understand feature distributions and potential outliers  
- Application of an Isolation Forest model to detect anomalies  
- Interpretation of anomaly scores and flagged observations  

## Model Choice
Isolation Forest is used due to its effectiveness in high-dimensional settings, ability to operate without labeled data, and computational efficiency. The model identifies anomalies by isolating observations that require fewer splits in randomly constructed trees.

## Results
The model outputs an anomaly score for each observation along with a binary anomaly flag. These results are used to highlight and analyze observations that deviate significantly from typical patterns in the data.

