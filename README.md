# Heart Failure Classification


## Overview
This project aims to classify heart failure into two classes: 0 (no heart failure) and 1 (heart failure). The dataset is preprocessed using label encoding, one-hot encoding, and Min-Max scaling. A Convolutional Neural Network (CNN) model is used for the classification task.

## Dataset
- **Classes**: 2 (0 for no heart failure, 1 for heart failure)
- **Data Preprocessing**:
  - **Label Encoding**: Converts categorical labels into numerical format.
  - **One-Hot Encoding**: Converts categorical features into a binary matrix representation.
  - **Min-Max Scaling**: Scales the feature values to a range between 0 and 1.

## Model Structure
The CNN model used for classification consists of the following layers:
- An input layer with 20 neurons, taking input of dimension 26 and using ReLU activation.
- A hidden layer with 15 neurons and ReLU activation.
- Another hidden layer with 8 neurons and ReLU activation.
- An output layer with a single neuron and sigmoid activation for binary classification.

The model is compiled with binary cross-entropy loss, Adam optimizer, and accuracy as the evaluation metric.

## Model Evaluation
The performance of the model is evaluated using the following metrics:
- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**
- **Confusion Matrix**
