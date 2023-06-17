# Credit-Card-Fraud-detection

![image](https://github.com/Velv8t19/Credit-Card-Fraud-detection/assets/58586824/b4f491e1-d88f-45ad-9e02-5d19cf1c0b7c)



ChatGPT
Credit card fraud is a widespread issue, affecting many individuals, banks, and online retailers. Developing a model that can detect fraudulent transactions can potentially save a significant amount of money. In this project, a dataset from Kaggle was utilized, consisting of 284,807 rows and 30 numeric columns, along with a class label indicating whether a transaction is fraudulent. The values in columns V1-V28 were likely obtained through PCA dimensionality reduction to safeguard user identities and sensitive information. Fortunately, the dataset does not contain any missing values.

To build the fraud detection model, the Random Forest algorithm was employed. Additionally, two techniques were applied to enhance the model's performance: normalization and SMOTE (Synthetic Minority Over-sampling Technique), which helps address imbalanced data.

For visualizing the data and evaluating the model's performance, the seaborn library was used. It provides useful tools for generating visualizations like confusion matrices. The code for this project was implemented in Jupyter Notebook, ensuring an interactive and collaborative environment for data analysis and model development.
