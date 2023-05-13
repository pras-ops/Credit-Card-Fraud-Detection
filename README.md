# Credit Card Fraud Detection


## Introduction

This project aims to detect fraudulent credit card transactions using machine learning techniques. The main goal is to prevent customers from being charged for items they did not purchase by recognizing unauthorized transactions.

## Motivation

Credit card fraud is a significant concern for both credit card companies and customers. It involves unauthorized transactions carried out using stolen credit card information, either through physical theft or digital means such as phishing or skimming. Detecting and preventing fraud is crucial to protect customers and maintain trust in the credit card system.

## Anomaly Detection

Anomaly detection, also known as outlier analysis, is a data mining technique used to identify data points, events, or observations that deviate from normal behavior within a dataset.

### Popular Algorithms:

1. **Isolation Forest**: This algorithm utilizes the concept of isolation to identify anomalies efficiently.

2. **OneClassSVM**: It is a support vector machine-based algorithm that separates normal and abnormal data points.

3. **Local Outlier Factor**: This algorithm measures the local deviation of a data point with respect to its neighbors to identify anomalies.

## PyCaret

PyCaret is an open-source, low-code machine learning library in Python. It streamlines the end-to-end machine learning process, enabling users to prepare data, build models, and deploy them quickly within their chosen notebook environment.

### Advantages of PyCaret:

1. **Increases Productivity**: PyCaret simplifies and automates many steps in the machine learning workflow, reducing development time.

2. **Easy to Use**: The library provides a user-friendly API, making it accessible to both beginners and experienced data scientists.

3. **Business Ready**: PyCaret supports various machine learning algorithms and evaluation metrics, ensuring models are ready for real-world deployment.

## Project Timeline

1. **Data Analysis**: Conducted exploratory data analysis to understand the characteristics of the dataset.

2. **Model Building using ML**: Developed a machine learning model using the Isolation Forest algorithm.

3. **Model Building using Auto ML**: Utilized PyCaret's Auto ML capabilities to build and compare multiple models.

## Results

The Isolation Forest model achieved an accuracy of 99.78% on the test set, with a precision of 0.36 for detecting fraudulent transactions. The classification report provides a detailed analysis of the model's performance.

1.  The OneClassSVM algorithm is known to have a longer runtime compared to other models due to its complexity.
2.  The PyCaret model comparison code may take longer to run due to its capability of testing multiple algorithms. This step ensures a comprehensive evaluation of various machine learning models, providing a better understanding of their performance and allowing for informed decision-making in selecting the most suitable model for credit card fraud detection

Additionally, here are the results for various other models:

- Random Forest Classifier (rf)
  - Accuracy: 0.9996
  - AUC: 0.9431
  - Recall: 0.7790
  - Precision: 0.9572
  - F1: 0.8583
  - Kappa: 0.8581
  - MCC: 0.8630
  - Training Time (Sec): 121.3450

- Extra Trees Classifier (et)
  - Accuracy: 0.9996
  - AUC: 0.9430
  - Recall: 0.7905
  - Precision: 0.9618
  - F1: 0.8666
  - Kappa: 0.8664
  - MCC: 0.8712
  - Training Time (Sec): 13.9700

- Extreme Gradient Boosting (xgboost)
  - Accuracy: 0.9996
  - AUC: 0.9739
  - Recall: 0.7994
  - Precision: 0.9471
  - F1: 0.8656
  - Kappa: 0.8654
  - MCC: 0.8692
  - Training Time (Sec): 84.5600

And more...

These results provide insights into the performance of different machine learning models in detecting credit card fraud.



## Usage

1. Clone the repository.
2. Install the necessary dependencies.
3. Run the notebook or script to replicate the results.
4. Explore the project and customize it for your specific needs.

Feel free to provide any feedback or suggestions for improvement.

## Conclusion

Credit card fraud detection is a critical task to protect customers and maintain the integrity of the credit card system. By leveraging machine learning techniques and PyCaret's capabilities, this project provides an effective solution for identifying fraudulent transactions.
