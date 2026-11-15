# Skin Cancer Detection – Melanoma Classification using Deep Learning

### 1. Introduction:
Skin cancer is one of the most common cancers worldwide. Early identification is crucial for effective treatment.
In this project, we create a Deep Learning model using Convolutional Neural Networks (CNN) with Transfer Learning (EfficientNetB0) to classify skin lesion images into two categories:
- **Benign**: Non-cancerous lesions
- **Malignant**: Cancerous melanoma lesions

### 2. Project Objectives:
- Load and explore the skin lesion image dataset.
- Build an efficient data loading pipeline with TensorFlow / Keras.
- Implement Transfer Learning using pre-trained EfficientNetB0.
- Train and evaluate the model using Accuracy, Precision, Recall, F1-Score, and ROC-AUC.
- Visualize training history, Confusion Matrix, and ROC Curve.
- Save and reload the trained model for inference.

###Model Performance

Metric                                  Test Result
Accuracy                                    90.8%

AUC                                         0.9699

Precision                                   92.5%

Recall                                       88.8%
Loss                                         0.2116