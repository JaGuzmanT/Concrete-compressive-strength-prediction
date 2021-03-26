# Concrete-compressive-strength-prediction using non-destructive tests

Compressive strength is the ability of a material or structure to withstand axial loads.

Compressive strength is one of the most significant measurable parameters of concrete. Usually, these tests are performed on concrete cylinders. Testing requirements differ from country to country depending on the design code.

## Description of the repository

This repository contains 2 folders with 1 notebook for each one.

Features: Ultrasonic pulse velocity (UPV), Electrical resistivity (Er), Resonance frequency (FR), and Compressive strength (CS).

Target: Compressive strength

Type of problem: Supervised and Regression problem

Regressor: Deep Neural Network, DNN for short.

1.- Preprocessing data-Folder
1. Preprocessing data.ipynb : This notebook contains the analysis of the dataset, Pearson correlation analysis, the features with the highest correlation values were selected and the correct generation that will fill the DNN.
If you want to try with your own dataset just need to change the Data_art.csv

2. DNN model-folder
2. DNN model.ipynb: In this notebook, you will find the DNN architecture, and you could compile it, obtaining the diagram plot model, the training and test loss, and the comparison between actual values against predicted values.

The DNN architecture could be enhanced, if you have a better option I would like to know. Enjoy it. 
