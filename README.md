# Parkinson-s Disease (PD) Prediction

## Table of Contents
- [Problem Statement](#Problem-Statement)
- [Data Dictionary](#Data-Dictionay)
- [Requirements](#Requirements)
- [Technologies](#Technologies)
- [Getting Started](#Getting-Started)

## Problem Statement
Parkinson’s disease (PD) is one of the major public health diseases in the world which is progressively increasing day by day and had its effect on many countries. Thus, it is very important to predict it at an early age which has been a challenging task among researchers because the symptoms of disease come into existence in either middle or late middle age. So this project focuses on using various machine learning techniques such as Logistic Regression, Random Forest, SVM, Decision Tree and KNeighbors algorithms. The prediction efficiency would be beneficial for patients who are suffering from Parkinson. Generally in the first stage, Parkinson can be cured by the proper treatment. So it‘s important to identify the PD at the early stage for the betterment of the patients. The main purpose of this work is to find the best prediction model.

## Data Dictionary
| Column Name| Data Type | Description |
| --- | --- | --- |
| name | object | ASCII subject name and recording number. |
| MDVP:Fo(Hz) | float64 | Average vocal fundamental frequency.|
| MDVP:Fhi(Hz) | float64 | Maximum vocal fundamental frequency. |
| MDVP:Flo(Hz) | float64 | Minimum vocal fundamental frequency. |
| MDVP:Jitter(%), MDVP:Jitter(Abs) | float64 | Measure of variation in fundamental frequency. |
| MDVP:RAP, MDVP:PPQ  | float64 | Measure of variation in fundamental frequency. |
| Jitter:DDP | float64 | Measure of variation in fundamental frequency. |
| MDVP:Shimmer, MDVP:Shimmer(dB) | float64 | Measures of variation in amplitude. |
| Shimmer:APQ3, Shimmer:APQ5 | float64 | Measures of variation in amplitude. |
| MDVP:APQ | float64 | Measures of variation in amplitude. |
| Shimmer:DDA | float64 | Measures of variation in amplitude. |
| NHR, HNR | float64 | Measures of ratio of noise to tonal components in the voice. |
| status | int64 | Health status of the subject (one) - Parkinson's, (zero) - healthy. |
| RPDE, D2 | float64 | Nonlinear dynamical complexity measures. |
| DFA | float64 | Signal fractal scaling exponent. |
| spread1,spread2,PPE | float64 | Three nonlinear measures of fundamental frequency variation. | 

## Requirements
- Anaconda.
- Jupyter Notebook.

## Technologies
The project is created with:
- Python.
- Pandas.
- Numpy.
- Matplotlib.
- Seaborn.
- Scikit learn

## Getting Started
To run this project, intall it locally using git bash:
1. Clone this repo (for help see this [tutorial](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository)).
2. Open the project in Jupyter notebook.
3. Run the project.
