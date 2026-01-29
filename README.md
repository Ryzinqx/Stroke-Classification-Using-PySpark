# Stroke Risk Prediction using Machine Learning 
This project aims to predict the risk of stroke health related features. The implementation is built using PySpark to handle prepocessing and model training. Multiple algorithm were explored and evaluated to identify the best performing model. The final model selection was made through comparatitve analysis and hyperparameter tuning to achieve optimal performance.

## Model Performance
Several models were evaluated in this project.
The tuned random forest model achieved the best result:
- Accuracy: 96.89%
- Precision: 97.66%
- Recall: 96.13%
- F1-score: 96.89%
- ROC-AUC: 0.9689
Due to class imbalance in the dataset, model evaluation focused on recall, F1-score, and ROC-AUC rather than accuracy alone.
