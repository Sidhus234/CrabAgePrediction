# CrabAgePrediction

DATA SCIENCE CASE STUDY

Gursewak Singh Sidhu
Sidhus234@gmail.com
Abstract: The challenge consist of making some sense out of those data. We're notably looking for a method to predict the age of a crab given its features

### For this project, below process is followed:
  1. Exploratory Data Analysis: Details covered in code files (01Crab_Age_Prediction_EDA.ipynb and 01Crab_Age_Prediction_EDA2.ipynb). 
  2. Linear Regression Model: Provides step by step process on how to select optimal Linear Regression Model (03Crab_Age_Prediction_LRModel.ipynb)
  3. Random Fores Model: Provides step by step process on how to select optimal Random Forest Regression Model (03Crab_Age_Prediction_RFModel.ipynb)
  4. GBM Model: Provides step by step process on how to select optimal GBM Regression Model (03Crab_Age_Prediction_GBMModel.ipynb)


### Required python config and libraries:
  1. The python version 3.6.9 was used to develop the model.
  2. Important libraries need to execute this code are:
     > Scikit-learn
     > Numpy
     > Pandas
     > Matplotlib
     > Pickle
     > Os
     > Warnings
     > Scipy
     > Statsmodel
     > 

Note: Please ensure all the above libraries, updated versions are installed. To replicate the results, open the jupyter notebook and just click on Kernal -> Restart and Run all


### Changes to be made are only in the variable:
  > Please follow the same folder structure, and the results should be replicated.

__Note:__ Results may not be 100% replicable, as project uses random grid search to select the best random forest and gbm model. The results would be close, but may not be exactly same. To ensure consistency, the final selected GBM and RF model is saved as a pickle file. To get exact results, please load this pickle file and score on the X_train and X_test datasets.

