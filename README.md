# ⚡ Energy Consumption Forecasting using RNN and LSTM 🔋

This project focuses on forecasting future energy consumption using historical data through Recurrent Neural Networks (RNN) and Long Short-Term Memory (LSTM) models. The goal is to predict energy consumption based on time-series data, demonstrating the effectiveness of deep learning techniques in handling temporal sequences.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Preprocessing](#preprocessing)
- [Model Architecture](#model-architecture)
  - [RNN](#rnn-model)
  - [LSTM](#lstm-model)
- [Training and Evaluation](#training-and-evaluation)
- [Models Comparison](#models-comparison)

## Overview 🌟

The project utilizes RNN and LSTM neural networks to forecast energy consumption. The models are trained on historical energy data to capture temporal dependencies and trends for future predictions. LSTM, being an advanced form of RNN, is more capable of handling long-term dependencies, making it ideal for time-series forecasting tasks like this.

## Dataset 📊

- The dataset contains time-series data of energy consumption.
- It includes features such as timestamps and energy consumption values.

The dataset is preprocessed to remove missing values, scale features, and split into training and testing sets for model evaluation.

## Preprocessing 🛠️

- **Missing Values Handling**: Rows with missing data are handled appropriately (e.g., imputation or removal).
- **Feature Scaling**: The data is normalized using MinMax scaling to improve model performance.
- **Train-Test Split**: The dataset is split into training (80%) and testing (20%) sets.

## Model Architecture 🏗️

### RNN Model

The Recurrent Neural Network (RNN) is a basic architecture for time-series prediction:
- Input Layer
- Multiple RNN Layers with Tanh activation
- Dense Output Layer for prediction

### LSTM Model

The Long Short-Term Memory (LSTM) model is built with the following architecture:
- Input Layer
- Multiple LSTM Layers with Tanh activation
- Dense Output Layer for prediction

## Training and Evaluation 📈

- **Loss Function**: Mean Squared Error (MSE) is used as the loss function.
- **Optimizer**: Adam optimizer is employed to minimize the loss function.
- **Evaluation Metric**: The model performance is evaluated using MSE and plotted to compare predicted versus actual values.

Both models are trained over several epochs, and their performance on the test set is evaluated to determine the accuracy of energy consumption forecasts.

## Results 🎉

- The models are compared based on their prediction accuracy on the test dataset.
- Plots of actual vs. predicted energy consumption are generated to visualize model performance.

(LSTM typically performs better than the standard RNN due to its ability to retain long-term dependencies.)

## Models Comparison ⚖️
![Models Comparison](https://github.com/user-attachments/assets/6e124a5e-7e78-49bdea-f895d6226126)
