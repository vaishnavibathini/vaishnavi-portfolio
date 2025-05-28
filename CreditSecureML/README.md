# CreditSecureML

CreditSecureML is a machine learning-based system designed for **credit risk prediction** and **fraud detection** in the financial domain. Built as part of my Master’s coursework at Lamar University, this project combines predictive analytics with real-world datasets to improve financial decision-making.

##  Features
- Credit risk prediction using **XGBoost** and **Logistic Regression**
- Fraud detection using **Random Forest** and **Logistic Regression**
- Real-world datasets: German Credit Dataset & Lending Club loan records
- Performance metrics: Accuracy, Precision, Recall, F1-Score
- Results indicate 97% fraud detection accuracy and insights into model biases

##  Tech Stack
- Python
- Scikit-learn
- XGBoost
- Jupyter Notebooks
- Pandas & Matplotlib

##  Structure
- `notebooks/`: Jupyter notebooks for training and testing
- `data/`: Raw datasets (not included here; see documentation)
- `models/`: Serialized model files (optional)

##  Sample Results

| Task              | Model             | Accuracy | Precision | Recall | F1-Score |
|-------------------|------------------|----------|-----------|--------|----------|
| Credit Prediction | XGBoost           | 86%      | 86%       | 11%    | 19%      |
| Fraud Detection   | Random Forest     | 97%      | 98%       | 83%    | 90%      |

##  Future Enhancements
- Deploy as a REST API
- Add explainable AI (SHAP)
- Real-time fraud streaming with Kafka/Spark

##  License
For educational purposes only.

