# Fraud Detection Project

## Overview
This project aims to detect fraudulent transactions using machine learning techniques. The dataset used for this project contains various features related to transactions, and the goal is to classify each transaction as either fraudulent or non-fraudulent.

## Dataset
The dataset includes features such as transaction amount, transaction type, and other relevant information. The data is preprocessed to handle missing values, normalize numerical features, and encode categorical variables.

## Model
A Random Forest classifier is used for this project. The model is trained on the preprocessed dataset and evaluated using various metrics such as accuracy, precision, recall, and F1-score.

## Results
The model achieved the following results on the test dataset:
- Accuracy: 95%
- Precision: 92%
- Recall: 90%
- F1-score: 91%

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

## Contributions
All suggestions to improve this project are welcome. Feel free to open issues or submit pull requests.
