# CrabAgePrediction

DATA SCIENCE CASE STUDY
Asia Miles
Gursewak Singh Sidhu
Sidhus234@gmail.com
Abstract
Document explains how to execute the codes to replicate the results
Files:
1. Asia Miles Data Science case study.ipynb: This is the jupyter notebook that was used to develop the model.
• It covers the below process:
▪ Exploratory data analysis
▪ Random Forest Model building (model selection and model performance)
▪ Gradient Boosting Model building (model selection and model performance)
▪ Linear regression (model selection and model performance)
• Required python config and libraries:
▪ The python version 3.6.9 was used to develop the model.
▪ Important libraries need to execute this code are:
1. Scikit-learn, numpy, pandas, matplotlib, pickle, os, warnings, scipy, statsmodel
Note: Please ensure all the above libraries, updated versions are installed. To replicate the results, open the jupyter notebook and just click on Kernal -> Restart and Run all
▪ Changes to be made are only in the variable:
o Direc: point it to directory where the raw data is saved in csv file
Note: Results may not be 100% replicable, as I have used random grid search to select the best random forest and gbm model. The results would be close, but may not be exactly same. To ensure consistency, the final selected gbm model is saved as a pickle file. To get exact results, please load this pickle file and score on the X_train and X_test datasets.
2. Asia Miles Data Science case study.html: This is the html version of the above jupyter notebook. Just open it in any available web browser (prefer chrome latest version or Microsoft edge).
3. Asia Miles.pptx: PowerPoint deck covering the basic data insights and model performance
4. Code_to_predict_age.py: Python code. This is the first part of submission. It accepts the raw data and generates a new csv file with “Predicted Age” variable. The instructions to execute it are documented in the code itself.
5. Code_to_give_model_metrics.py: Python code. This is the second part of submission. It accepts the last code’s output csv file and give model performance metrics. The performance here would be different than the one documented in model because, this code scores the whole data (train and test combined), with no outlier observations being excluded.
6. GBM_Regressor.sav: GBM selected model, saved as a pickle file.
