# Data Exploration Project - Tanzanian Pumps Dataset

The contents of this repository were created as part of the exam for the lecture *Applied Machine Learning Fundamentals - Data Exploration Project* at DHBW Ravensburg as a group project.

**Problem:**
The given dataset contains information on pumps in Tanzania. In addition to information on water quality, type of pump, installer, etc. and various geographical features, the data set also contains the maintenance status of the pumps.

**Objective:**
The objective is to predict this maintenance status of the pumps using Machine Learning models. The corresponding target variable is the column "status_group", containing the values "functional", "functional needs repair" and "non functional". More specifically, three models are to be created:

- Prediction model distinguishing functional and non-functional pumps (Prediction Model 1). 
- Prediction model detecting pumps that need to be repaired (Prediction Model 2).
- Prediction model distinguishing between all three classes (Prediction Model 3). 

Thus these tasks are classification problems (two binary, one multinomial) of supervised learning.

**Metrics:**
The goodness of the models is to be measured by the AUC (Area Under Curve) of the test data.

The goal is to create a complete notebook from data import, through EDA to data preparation, model building, analysis and validation following CRISP-DM.


### Contents: 
- *project.ipynb*: This notebook contains the entire process, from EDA and Data Preparation to the training and optimization of prediction models (1-3) as well as their evaluation
- *project.slides.html*: The notebook above as .html-File
- *pump_train.csv*: The datas set used for training (train set)
- *pump_test.csv*: The data set used for an out-of-sample evaluation of the trained models (test set)
- *misc*: This directory contains various other notebooks that have emerged in the course of the project. This includes an analysis on feature importances as well as various notebooks on EDA, giving even deeper and more detailed insights than the plots provided in *project.ipynb*. Please note that all files in the *misc*-directory have not been cleaned up and may also contain outdated information and code.


### Contributors:
- [@OhItsLena]
- [@FabianLulikat]
- [@timo282]
_______________
