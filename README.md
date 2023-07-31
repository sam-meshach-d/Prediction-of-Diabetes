# Prediction of Diabetes using Machine Learning

## Overview

Diabetes is considered one of the deadliest and chronic diseases, leading to an increase in blood sugar levels. Early identification and treatment of diabetes are crucial to prevent complications. This project aims to design a model that can predict the likelihood of diabetes in patients with maximum accuracy using machine learning classification algorithms. 
Two popular algorithms, Decision Tree and Support Vector Machine (SVM), are employed to detect diabetes at an early stage. The experiments are conducted on the Pima Indians Diabetes Database (PIDD) sourced from the UCI Machine Learning Repository.

## Dataset

The dataset used in this project is the Pima Indians Diabetes Database, which contains various features related to patients' health, such as glucose levels, blood pressure, BMI, age, and pregnancy history. Each data instance is labeled as either diabetic or non-diabetic.

**Dataset source:** UCI Machine Learning Repository

## Requirements  
To run the code and reproduce the experiments, the following libraries and dependencies are required:

Python (>= 3.6)  
NumPy  
Pandas  
Scikit-learn  

You can install the required libraries using the following command:

```pip install numpy pandas scikit-learn```  

Usage  

Clone the repository:

```git clone https://github.com/sam-meshach-d/prediction-of-diabetes.git```  

Navigate to the project directory:  

```cd prediction-of-diabetes```

Install the required dependencies as mentioned in the "Requirements" section.

Execute the Jupyter Notebook or Python script to perform the experiments:

Run Impl.ipynb in Jupyter Notebook.
Alternatively, run diabetes_prediction.py using Python.

## Results and Evaluation
The performances of both Decision Tree and Support Vector Machine algorithms are evaluated on various measures such as Precision, Accuracy, F-Measure, and Recall. Accuracy is measured over correctly and incorrectly classified instances. The results are presented and analyzed in the Jupyter Notebook and the Python script.
Additionally, Receiver Operating Characteristic (ROC) curves are used to verify and visualize the performance of the models in a systematic manner.

## Conclusion
By leveraging machine learning classification algorithms, this project seeks to enhance the early detection of diabetes in patients. The model's performance is evaluated using various metrics and visualized using ROC curves, providing valuable insights into its effectiveness.

Feel free to contribute, report issues, or provide feedback to improve the project further.

Happy Predicting!
