# Fraud Detection Project 🔍💰

## Overview 🚀
This project aims to detect fraudulent credit card transactions using machine learning techniques. The main objective is to classify transactions as either fraudulent or legitimate, providing insights into the potential financial impact of fraud.


## Why is this project relevant?
🌐 Real-world Impact : An efficient fraud detection system prevents financial losses and protects consumers from identity theft.


## Model 🤖
A Random Forest classifier is employed to learn from the preprocessed dataset. The model is evaluated using metrics such as accuracy, precision, recall, and F1-score.
## Dataset 💾
The dataset contains anonymized credit card transactions from September 2013, recorded by European cardholders. With 284,807 transactions and 492 confirmed frauds, the data is highly imbalanced (frauds represent only 0.172% of all transactions).

It includes numerical features resulting from a PCA transformation, except for two features:
- **Time**: Seconds elapsed between each transaction and the first one.
- **Amount**: The transaction amount.
- **Class**: Response variable (1 for fraud, 0 for non-fraud).

You can access the original dataset here: [Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).


## Results 📈
- **Accuracy**: 95%
- **Precision**: 92%
- **Recall**: 90%
- **F1-score**: 91%

📄 For practical visualization of the results, including the outputs of the code, please refer to the PDF file: pdf_fraud-detection.pdf.

## Financial Impact 💰
For simulation purposes, an average fraudulent transaction value of **€500** was assume.  
With a recall of 90%, the model identified approximately 443 frauds and missed 49 cases, leading to a hypothetical financial impact of:  
- **Impact**: 443 × €500 = **€221,500**

> **Note:** The **€500** value is purely hypothetical and used for simulation purposes—it is not derived from the dataset.

## Usage 💻
To run the project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Olivvvrr/fraud-detection.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd fraud-detection
   ```
3. **Install the dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
4. **Launch the Jupyter Notebook to explore the analysis:**
   ```bash
   jupyter notebook fraud-detection.ipynb
   ```

## Conclusion ✅
This project demonstrates how machine learning can be leveraged for fraud detection. While the Random Forest classifier achieved solid results, further enhancements—such as advanced models and feature engineering—could boost performance even more.

## License 📄
This project is licensed under the MIT License.

## System Objective 🎯
Automate the detection of fraudulent credit card transactions to improve efficiency and reduce financial losses.

## Importance ⚠️
Credit card fraud affects millions worldwide, leading to significant financial losses. This project shows a practical approach to mitigating these risks and enhancing security.

## Future Improvements 🔜
- **Continuous Monitoring:** Implement a feedback loop to update the model as new data becomes available.
- **Advanced Techniques:** Explore deep learning and other sophisticated models.
- **Optimization:** Fine-tune hyperparameters for even better performance.
- **Feature Engineering:** Develop new features to enhance predictive accuracy.
- **Integration:** Incorporate MySQL for data storage and querying, and develop APIs and dashboards for real-time monitoring.

## Contributions 🙌
Contributions, feedback, and suggestions are highly welcome! Feel free to open issues or submit pull requests.

## Note 📝
This documentation is continuously updated as new features and improvements are added. Your insights and suggestions are greatly appreciated.

---

If you have any questions or ideas, feel free to reach out! Happy coding! 🚀
