# RUL Prediction with LSTM and GRU

This project focuses on predicting the Remaining Useful Life (RUL) of engines using LSTM and GRU neural networks. The model processes multivariate time series data from multiple sensors and is built using deep learning techniques.

## Overview

The `main_rul.ipynb` notebook contains all the necessary code for data preprocessing, model building, training, evaluation, and comparison of LSTM and GRU models. The notebook walks through the following steps:
- Data preprocessing (handling missing values, normalization)
- Time series data preparation (creating sequences of 50 steps)
- Model architecture for LSTM and GRU
- Training both models
- Evaluation of models with metrics (Accuracy, Precision, Recall, F1-score)
- Sensor data analysis to detect noisy sensors

## Libraries Used

The project makes use of the following Python libraries:
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computing and array operations.
- **Matplotlib**: For plotting graphs.
- **Keras (TensorFlow backend)**: For building and training LSTM and GRU models.
- **scikit-learn**: For model evaluation metrics like precision, recall, and F1-score.
- **os**: For interacting with the file system.

## How to Run

1. **Install the necessary libraries**: You can install the required libraries via pip:

   ```bash
   pip install pandas numpy matplotlib keras scikit-learn

2. **Download Data**: Use the FD001 dataset from the NASA CMAPSS Turbofan Engine dataset. Download the CMAPSSData.zip from NASA Open Data Portal and use FD001 dataset.