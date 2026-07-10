# Deep Learning Course Project: Anomaly Detection

This repository contains a student project developed for the Deep Learning course.

The purpose of this project is to implement and evaluate machine learning and deep learning techniques for anomaly detection in network security data.

This project is developed only for academic and educational purposes and is not intended to be used as an industrial security system or a production-ready solution.

## Objective

The main objective of this project is to implement a two-stage anomaly detection framework for identifying abnormal network behaviors using a combination of deep learning and unsupervised machine learning methods.

The proposed framework combines a Stacked Autoencoder for feature extraction and reconstruction error analysis with an Isolation Forest model for final anomaly detection.

## Implemented Methods

### Stacked Autoencoder

- Deep learning-based representation learning using normal data samples
- Extraction of latent features from high-dimensional network data
- Dimensionality reduction through latent space representation
- Reconstruction error calculation as an additional anomaly indicator

### Isolation Forest

- Unsupervised anomaly detection algorithm applied to extracted features
- Detection of abnormal patterns based on latent features and reconstruction error
- Final classification of Normal and Attack samples

## Dataset

The experiments were performed using the **LMD-2023 dataset**, which contains Sysmon-based event logs for lateral movement and network security analysis.

The dataset includes Normal and Attack samples used for training, evaluation, and anomaly detection experiments.

## Preprocessing Steps

The following preprocessing operations were applied:

- Data cleaning and feature selection
- Label transformation
- Removal of irrelevant features
- Min-Max Scaling for numerical features

## Evaluation Metrics

The implemented model was evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC

## Results

The final two-stage anomaly detection model achieved the following results on the test dataset:

- Accuracy: 0.885
- Precision: 0.374
- Recall: 0.727
- F1-score: 0.494
- ROC-AUC: 0.935

The results indicate that the proposed framework can effectively distinguish abnormal behaviors from normal network activities.

## Tools and Libraries

- Python
- TensorFlow / Keras
- Scikit-learn
- Pandas
- NumPy
- Matplotlib

## Reference

Related work:

**Smiliotopoulos, C., Kambourakis, G., and Barbatsalou, K.**  
**"Assessing the Detection of Lateral Movement Through Unsupervised Learning Techniques"**

## Author

Student Project – Deep Learning Course
