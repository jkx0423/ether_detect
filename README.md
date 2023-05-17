# ether_detect

Fraudulent behavior detection in Ethernet.

In this project, used a dataset on kaggle about ethereum.

The dataset: https://www.kaggle.com/datasets/vagifa/ethereum-frauddetection-dataset

For this dataset data reading and cleaning, data visualization, and training of the data using the model were performed. Fraud detection in ethereum was performed.

The models used include logistic regression, random forest, XGB, Light Gradient Boosting Machine, Gaussian Naive Bayes and Hyperparameters tuning for XGB Classifier six models.

For fraud detection, detecting the presence of fraud as the absence of fraud can lead to greater losses, so we are more concerned about the recall value than the accuracy. 

In this project, we mark the presence of fraud as 1 and the absence of fraud as 0.

For Logistic Regression Model, the recall value: 0.88, the accuracy: 0.88

For random forest Model, the recall value: 0.94, the accuracy: 0.97

For XGB Model, the recall value: 0.95, the accuracy: 0.98

For Light Gradient Boosting Machine Model, the recall value: 0.95, the accuracy: 0.98

For Gaussian Naive Bayes Model, the recall value: 0.53, the accuracy: 0.64

For Hyperparameters tuning for XGB Classifier Model, the recall value: 0.95, the accuracy: 0.98

