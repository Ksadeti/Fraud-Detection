🚨 Credit Card Fraud Detection with Machine Learning & Deep Learning

This project tackles the challenge of detecting fraudulent credit card transactions using a mix of interpretable and advanced models. I combined statistical analysis, logistic regression, convolutional neural networks (CNNs), and XGBoost to identify fraud patterns in highly imbalanced data.

🧪 Hypothesis Testing

Using a two-sample t-test, I confirmed that fraudulent transactions involve significantly different amounts than legitimate ones (p = 0.0032), validating the predictive power of the Amount feature.

🧠 Models & Results

1. Logistic Regression
ROC-AUC: 0.972

Precision: 0.76 | Recall: 0.45

✅ Interpretable baseline

⚠️ Misses many frauds despite high overall accuracy

 
 Convolutional Neural Network
ROC-AUC: 0.992 | PR-AUC: 0.912
Precision: 0.99 | Recall: 0.77 (tuned)


3. XGBoost (Tuned via RandomizedSearchCV)
ROC-AUC: 0.984 | PR-AUC: 0.880
Precision: 0.86 | Recall: 0.86

🔥 Best performance among models

🛡️ Strong fraud detection with minimal false alarms

✅ Conclusion

XGBoost is the top-performing model for production, balancing recall and precision with minimal false positives.

CNN is ideal for fast, real-time inference.

Logistic regression remains useful for interpretability and compliance use cases.

