# AIS Vessel Position Prediction
TDT4173 - Moderne maskinlæring i praksis
Markus Sandnes
André Joseph Virani

## Overview
This project is part of the TDT4173 - Modern Machine Learning in Practice course. The main objective is to predict the future positions of vessels based on Automatic Identification System (AIS) data from January 1st, 2024 to May 7th, 2024. The task involves building a machine learning model capable of forecasting vessel positions for five days into the future based on a range of factors such as congestion, port calls, and other relevant events affecting the vessels’ journey.

## File overview:
[Project description](Machine_learning_task_for_TDT4173.pdf) - a brief introduction to the task  
[Dataset definitions and explanation](Dataset_definitions_and_explanation.pdf) - a documents that gives more details about the dataset and column names  
[Training data](ais_train.csv) - training data       
[Test input data](ais_test.csv) - test input data  
[Optional data](schedules_to_may_2024.csv) - optional data that contains schedules for some vessels  
[Optional data](ports.csv) - optional data related to ports           
[Optional data](vessels.csv) - optional data related to vessels         
[Example submission](ais_sample_submission.csv) - a demo submission to Kaggle what predicts all zeroes  
[Jupiter Notebook demo](vessel_trajectories_visualization.ipynb) - a demo utility function for visualizing the trajectory of a vessel  
[Score function](kaggle_metric.ipynb) - the score function we use in the Kaggle competition  
