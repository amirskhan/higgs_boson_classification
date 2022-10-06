# Higgs Boson Classification
The ATLAS experiments at CERN uses Large Hadron Collider to produce Higgs boson particles to study about their nature. But these particles are very rare to occur. So it becomes essential to develop powerful machine learning algorithms to detect these particles. In this project I will be using machine learning algorithms from RAPIDS framework to classify between Higgs boson and a background process. The dataset is huge and handling large datasets with millions of rows and columns is difficult for Pandas. RAPIDS provides cuDF library for data preprocessing and analysis. I will be using cuDF to load the data, perform exploratory data analysis, and preprocess the data. I will use cuML library to train multiple models using GPU and compare the model results. The evaluation of the models will be done using confusion matrix and classification report. And, also the same algorithms will be trained on CPU using Scikit-Learn to compare the results between CPU and GPU. 

The whole project is distributed into 3 juyter notebooks, they are data_preprocessing.ipynb, training.ipynb, evluation.ipynb. Please refere to the notebooks for more details. The notebooks should be followed in the following order.
1. data_preprocessing.ipynb
2. training.ipynb
3. evluation.ipynb
