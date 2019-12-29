# posenet_predictor

MODELS USED:
1) Random Forest 
2) Decision Tree 
3) K-NN
4) XGBoost

MODEL TRAINING:
From the CSV data given to us, we performed data processing and removed the columns which were considered as “Noise” in the data. For e.g.: We do not need “Left Ankle” score and X and Y positions. Hence, we didn’t take into account such columns. Initially we tried to split the dataset into training and test set for training the model, then, we included the whole dataset as training set and trained the model, the later produced better accuracy.

DATA PRUNING:
We pruned the dataset to obtain only the relevant features to predict the required label.
Following are the list of features we considered to train and test the model:

• Left shoulder
• Right shoulder
• Left Elbow
• Right Elbow
• Left Wrist
• Right Wrist
• Left hip
• Right hip

This Zip Archive consists of :
1) Source code of your service under “src” folder (flask_server.py)
2) ML model training notebooks or scripts under “notebook” folder (KNN.py , DecisionTree.py
,RandomForest.py, xgBoost.py)
3) ML models under “models” folder
4) Assignment 2 Model Report

Procedure to Test the Server :
As we are using Ngrok service coupled with Python Flask to host our server, it will change the URL every 8 hours. Please let us know when you will be testing the assignment as we need to keep our services running during that time and we’ll update the Service URL in the provided excel sheet.
