# Anomaly-Detection-in-Medical-Imaging
Implementation of Deep Learning models to detect medical anomalies

Model Implemented: Convolutional Neural Networks

Datasets Used: 

Brain MRI dataset: https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset

Chest X-rays NIH dataset: https://www.kaggle.com/datasets/nih-chest-xrays/data

Type: Brain MRI Scans

Train-Test Split: 80:20

Applied 5-Fold Cross Validation

Results achieved:

![download](https://github.com/user-attachments/assets/85169ac6-bb98-458d-b9f9-8a21d561c3cb)

Classification Report:

              precision    recall  f1-score   support

    No Tumor       0.97      0.94      0.96       906
       Tumor       0.88      0.94      0.91       405

    accuracy                           0.94      1311
    macro avg       0.92      0.94      0.93      1311
    weighted avg       0.94      0.94      0.94      1311
