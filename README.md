Prediction of Chronic Diseases (Heart Disease and Diabetes)
This repository contains code and resources for predicting chronic diseases such as heart disease and diabetes using machine learning models. It includes datasets, research papers, and Python programs for model implementation and evaluation.

Repository Structure
The repository is organized into the following folders:

1. Datasets
This folder contains datasets used for training and testing the prediction models.

diabetes1.csv: Dataset for predicting diabetes, containing patient data related to diabetes.
heart_failure_clinical_records_dataset.csv: Clinical data for predicting heart failure.
heart.csv: Dataset containing various medical features used to predict heart disease.
modified_diabetes2.csv: A modified version of the diabetes dataset used for additional testing.

2. Paper
This folder contains the research paper that outlines the methods, experiments, and results related to this project.

Research_Paper_Word_File: The research paper in .docx format.
Research_Paper_Pdf_File: The research paper in .pdf format.

3. Program
This folder contains Python programs used for building the prediction models and evaluating their performance.

ROC.py: Script for calculating and plotting the Receiver Operating Characteristic (ROC) curve to evaluate model performance.
app3.py: The main Python application that predicts heart disease and diabetes based on input features using Streamlit for the user interface.
app3.dupl.py: A duplicate version of the main application, included for reference.
Requirements
To run the Python scripts, ensure you have the following libraries installed:

Python 3.x
pandas
scikit-learn
matplotlib
numpy
Streamlit (for the web app interface)
flask (if using the web app)
Install the necessary packages using pip:


pip install -r requirements.txt
Alternatively, to install Streamlit and other dependencies, you can run:


pip install pandas scikit-learn matplotlib numpy streamlit flask
Usage
Predicting Chronic Diseases:

Run the app3.py script to predict the likelihood of heart disease or diabetes based on the given datasets using Streamlit.

streamlit run app3.py
This will launch the application in your browser, where you can input health data to get predictions on heart disease or diabetes.

ROC Curve Analysis:

Use the ROC.py script to generate ROC curves for the prediction models, providing insights into model performance.

python ROC.py
Datasets
The datasets used for this project are in CSV format and can be found in the Datasets folder. These datasets contain medical records and patient information that are used to train machine learning models for disease prediction.

Research Paper
The research paper provides a comprehensive overview of the problem statement, the datasets used, model selection, results, and future scope. It is available in both Word and PDF formats in the Paper folder.

Contributions
Contributions are welcome! If you want to contribute, please fork the repository, create a feature branch, and submit a pull request.
