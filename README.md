# Credit Default Risk Model

This project trains a machine learning model on a dataset of over 307,000 loan applications from Home Credit Group to predict the likelihood of loan repayment by an applicant. The model takes in six features of an applicant and outputs a binary prediction of either 0 or 1, where 0 indicates that the applicant is likely to repay the loan and 1 indicates that the applicant is unlikely to repay the loan. This is intended to be a learning exercise in data preprocessing, EDA, and machine learning. Contributions and suggestions are welcome, and the project will continue to be updated with new features and improvements.

## Dataset
The dataset used in this project was obtained from Kaggle. The dataset includes information on loan applicants such as their age, gender, income, credit history, and other factors that might affect their likelihood of repaying a loan.

## Usage 
1) Clone the repository to local machine
2) Open borrowers_creditworthiness.ipynb and create an instance of the 'CreditDefault' class.
3) Use the 'predict' method on new applicant data. The 'predict' method takes a pandas DataFrame as input containing the loan applicant information to be predicted, and returns an array of binary predictions for each loan applicant.

## License
The dataset used in this project is licensed under the Open Database License (ODbL) v1.0. Please see the Kaggle competition page for more information on the license and terms of use.

## Credits
This project was created by Sam Pence. Special thanks to Home Credit Group and Kaggle for providing the dataset used in this project.
