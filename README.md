# Overview

This project aims to predict whether a customer will purchase additional health insurance products based on their existing insurance policies and demographic information.

# Dataset
The dataset contains the following information:

id : Unique ID for the customer

Gender : Gender of the customer

Age : Age of the customer

Driving_License 0 : Customer does not have DL, 1 : Customer already has DL

Region_Code : Unique code for the region of the customer

Previously_Insured : 1 : Customer already has Vehicle Insurance, 0 : Customer doesn't have Vehicle Insurance

Vehicle_Age : Age of the Vehicle

Vehicle_Damage :1 : Customer got his/her vehicle damaged in the past. 0 : Customer didn't get his/her vehicle damaged in the past.

Annual_Premium : The amount customer needs to pay as premium in the year

PolicySalesChannel : Anonymized Code for the channel of outreaching to the customer ie. Different Agents, Over Mail, Over Phone, In Person, etc.

Vintage : Number of Days, Customer has been associated with the company

Response : 1 : Customer is interested, 0 : Customer is not interested

# Methodology

## Data Exploration:

Analyze the dataset for missing values, outliers, and data distributions.

Visualize the data to understand relationships between variables.

## Feature Engineering:

Create new features if necessary to improve model performance.

Handle categorical variables using appropriate encoding techniques (e.g., one-hot encoding, label encoding).

## Model Selection:

Experiment with different machine learning algorithms (e.g., logistic regression, random forest, gradient boosting) to find the most suitable model for the task.

Evaluate model performance using appropriate metrics (e.g., accuracy, precision, recall, F1-score).

## Model Training:

Split the dataset into training and testing sets.

Train the selected model on the training set.

## Model Evaluation:

Evaluate the model's performance on the testing set using the chosen metrics.

Fine-tune the model if necessary.

## model comparison:

Use the trained models and compare their accuracy.

![image](https://github.com/user-attachments/assets/d45f9920-f9be-4ad9-9b28-f4f21ee2a657)


# Additional Notes
Consider using techniques like cross-validation to assess model performance more reliably.

Explore feature importance to understand which factors contribute most to the prediction.

Implement a deployment pipeline to integrate the model into a production environment.

# Dashboard
![bi](https://github.com/user-attachments/assets/b45f1d82-58cd-40cd-ad50-58e04d790c6f)

