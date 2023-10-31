# Real Estate housing prediction

This project focuses on developing a predictive system for housing prices in Boston, Massachusetts, utilizing the Boston Housing dataset. The primary objective is to identify the best model for this task and subsequently enhance its performance through hyperparameter tuning. Model evaluation will be conducted based on the Root Mean Squared Error (RMSE) on the test dataset, comprising 10% of the data with a random seed set to 42. 

A neural network will be used as the primary method to find a solution for this prediction task.

The **parse_csv** function is designed to parse individual lines of a CSV file and extract the independent and dependent variables, preparing them for further use in data processing or modeling. This function is essential for preprocessing the Boston Housing dataset before using it for machine learning tasks.

The **standardize** function is used to standardize the independent variables in the dataset. Standardization helps ensure that the data has a mean of 0 and a standard deviation of 1. The **ds_std** dataset is then created by applying this standardization to the original dataset. 

The **augment** function is used to introduce random noise to the independent variables in the training dataset, simulating data augmentation. Data augmentation is a common technique to increase the diversity of the training data, which can help the model generalize better. The training dataset is then augmented by repeating it 10 times and applying the augment function to each element. 


