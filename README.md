# Hospitalization Risk in Mexico

### Objective
The objective of this project is to predict if a person that got positive in a test fot the viral infection COVID19 is likely to be hospitalized or not. This is a project only for educational porpuses and may not have an incredibly good accuracy as expected for a real prediction tool.

### Data
The data set used is provided by the Epidemiological Surveillance System for Viral Respiratory Diseases of Mexico and contains information about all the COVID19 related cases, including positive and negative tested people. This data set can be downloaded in [here](https://datos.gob.mx/busca/dataset/informacion-referente-a-casos-covid-19-en-mexico).

### Analysis
Five different machine learning algorithms were compared to see which one gave the best results. The algorithms are:
* Logistic Regression
* Decision Tree Classification
* Boosted Random Forest
* Gaussian Naive Bayes
* XGBoost
The winner model was XGBoost and that is the one that will be fine tuned in order to improve its performance.