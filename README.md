# deep-learning-challenge
## Overview
This project aims to build a deep learning model that predicts whether an organization funded by Alphabet Soup is likely to succeed. By analyzing historical funding data, the model helps Alphabet Soup make better decisions about which organizations to support.

## Dataset
The dataset includes over 34,000 records of organizations and their funding success. Key columns include:

Features: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT, and the processed NAME column.
Target: IS_SUCCESSFUL (1 = Successful, 0 = Unsuccessful).

## Steps
Data Preprocessing:

Dropped unnecessary columns like EIN.
Grouped rare categories in APPLICATION_TYPE, CLASSIFICATION, and NAME.
Converted categorical data into numerical format using one-hot encoding.
Scaled numerical features using StandardScaler.
Model Development:

Built a neural network with two hidden layers (128 and 64 neurons).
Used ReLU activation for hidden layers and Sigmoid for the output layer.
Trained the model for 100 epochs to achieve 78.7% accuracy.
Optimization:

Improved accuracy by feature engineering on NAME and categorical columns.
Increased model capacity by adjusting neurons and layers.

## Results
Final Accuracy: 78.7%
The model exceeded the target accuracy of 75%.

