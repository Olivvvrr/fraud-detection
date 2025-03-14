# Fraud Detection Project

## Overview
This project aims to detect fraudulent transactions using machine learning techniques. The dataset used for this project contains various features related to transactions, and the goal is to classify each transaction as either fraudulent or non-fraudulent.

## Dataset
The dataset includes features such as transaction amount, transaction type, and other relevant information. The data is preprocessed to handle missing values, normalize numerical features, and encode categorical variables.

The dataset used in this project can be found at the following link: [Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud). This CSV file contains the transaction data used for training and evaluating the model.

### Summary
The dataset contains transactions made by credit cards in September 2013 by European cardholders. It presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, with the positive class (frauds) accounting for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, the original features and more background information about the data cannot be provided. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction amount, which can be used for example-dependent cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

## Model
A Random Forest classifier is used for this project. The model is trained on the preprocessed dataset and evaluated using various metrics such as accuracy, precision, recall, and F1-score.

## Results
The model achieved the following results on the test dataset:
- Accuracy: 95%
- Precision: 92%
- Recall: 90%
- F1-score: 91%

## Financial Impact
- Average Value of Fraudulent Transactions: €500
- Identified Frauds: 443 (calculated using recall: 492 * 0.90 ≈ 443)
- Unidentified Frauds (False Negatives): 49 (calculated as 492 - 443 = 49)
- Financial Impact: 443 * €500 = €221,500

## Usage
To run the project, follow these steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/Olivvvrr/fraud-detection.git
   ```
2. Navigate to the project directory:
   ```bash
   cd fraud-detection
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook to see the analysis and results:
   ```bash
   jupyter notebook fraud-detection.ipynb
   ```

## Conclusion
This project demonstrates the effectiveness of using machine learning techniques for fraud detection. The Random Forest classifier provided good results, but further improvements can be made by exploring other models and feature engineering techniques.

## License
This project is licensed under the MIT License.

## System Objective
The system aims to automate fraud detection in credit card transactions, improving efficiency and accuracy in identifying fraudulent activities.

## Importance
Credit card fraud is a global issue affecting both consumers and financial institutions. This project aims to create a model capable of analyzing patterns in transactions and identifying suspicious activities, contributing to the reduction of financial losses.

## Why is this project relevant?
### Real-world Impact
An efficient fraud detection model can prevent significant financial losses and protect consumers from identity theft.

## Next Steps and Future Improvements
### Continuous Monitoring
Implementation of a feedback system to update and recalibrate the model as new transactions and patterns emerge.

### Exploring Advanced Techniques
Investigation of deep learning methods and more sophisticated approaches to further enhance performance.

### Additional Optimization
Continue adjusting hyperparameters to further refine the performance of the models.

### Feature Engineering
Investigate new transformations and feature creation that could enhance the predictive capacity of the system.

### Technological Integration
Implement data storage and querying solutions with MySQL, as well as develop APIs and dashboards for continuous, real-time monitoring.

Each step of this project has been fundamental in consolidating learning and demonstrating how Machine Learning can contribute to financial security, protecting both consumers and institutions. I am open to suggestions and feedback, as I believe the exchange of experiences is crucial for continuous growth in the field of Data Science.

## Contributions
All suggestions to improve this project are welcome. Feel free to open issues or submit pull requests.

## Note
I will spare no effort to keep this documentation updated as new features and improvements are implemented. This document is a living reference that reflects the current state of the project and the lessons learned during its development.

###
If you work in Data Science or are interested in the subject, I would be happy to hear your suggestions or feedback!
