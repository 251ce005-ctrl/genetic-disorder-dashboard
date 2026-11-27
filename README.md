# Genetic Disorder Risk Prioritization Platform

## Project Overview
The Genetic Disorder Risk Prioritization Platform is a machine learning-based project designed to predict genetic disorder categories and prioritize patient records.

The project uses the XGBoost machine learning algorithm to classify genetic disorders and generate priority levels for patient records. A Streamlit dashboard is developed to display the prediction results in an interactive and user-friendly format.

## Problem Statement
Identifying and prioritizing genetic disorder cases from large datasets can be time-consuming. This project aims to use machine learning to support the analysis of genetic disorder data and help organize patient records based on predicted priority levels.

## Objectives
- To analyze genetic disorder dataset records.
- To predict genetic disorder categories using XGBoost.
- To classify patient records into High, Medium, and Low priority levels.
- To develop an interactive dashboard for displaying results.

## Technologies Used
- Python
- Pandas
- Scikit-learn
- XGBoost
- Streamlit
- Matplotlib
- Google Colab

## Machine Learning Algorithm
**XGBoost (Extreme Gradient Boosting)** is used for genetic disorder classification.

The model achieved an accuracy of **95.33%** on the evaluation data used in this project.

## Project Workflow
1. Collect the genetic disorder dataset.
2. Load and preprocess the dataset.
3. Train the XGBoost classification model.
4. Evaluate the model performance.
5. Predict genetic disorder categories.
6. Assign priority levels to patient records.
7. Display the results using a Streamlit dashboard.

## Dashboard Features
- Display total patient records.
- Show High, Medium, and Low priority counts.
- Visualize patient priority distribution using a bar chart.
- Search records by predicted genetic disorder category.
- View prediction results in a table.
- Download prediction results as a CSV file.

## Project Files
- `Genetic_Disorder_Project.ipynb` – Jupyter notebook containing the machine learning workflow.
- `app.py` – Streamlit dashboard application.
- `patient_priority_results.csv` – Generated prediction and priority results.
- `requirements.txt` – Required Python libraries.

## Result
The project successfully classifies genetic disorder categories and displays patient priority results through an interactive dashboard.

## Conclusion
This project demonstrates how machine learning can be used to analyze genetic disorder data and organize patient records for easier review. The dashboard provides a simple way to explore and download the generated results.

## Disclaimer
This project is developed for academic and educational purposes only. The predictions are not medical diagnoses and should not be used as a substitute for professional medical advice.
