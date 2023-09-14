# Convolutional Neural Network for Image Classification

This Python script demonstrates the use of Convolutional Neural Networks (CNNs) for image classification using TensorFlow and Keras. The code is designed to train a CNN model for image classification tasks with data augmentation and validation.

## Prerequisites

Before running the code, ensure you have the following libraries and tools installed:

- Python (3.6+)
- TensorFlow (2.x)
- NumPy
- scikit-learn
- Glob (usually comes with Python)
- OS (usually comes with Python)

You can install the required libraries using pip:


    ```bash
     pip install tensorflow numpy scikit-learn


## Usage
1. Organize your dataset into two folders: 'Training' and 'Validation.' Place your training images in the 'Training' folder and validation images in the 'Validation' folder.

2. Update the train_path and valid_path variables with the correct paths to your dataset folders in the script.

3. Adjust hyperparameters and model architecture as needed in the script.



   
1. After training is complete, the script will print the validation loss and accuracy.
## Data Augmentation
The script uses data augmentation for the training dataset, which includes random rotation, width shift, height shift, shear, zoom, and horizontal flip. This helps improve the model's robustness and generalization.

## Model Architecture
The CNN model consists of three convolutional layers with max-pooling followed by fully connected layers with dropout to prevent overfitting. The output layer has two neurons for categorical classification.

## Evaluation
After training, the model's validation accuracy will be displayed in the terminal. You can use additional evaluation metrics such as accuracy_score, precision_score, recall_score, and f1_score from scikit-learn to evaluate the model further.

## Example
In this example, the CNN achieved an accuracy of approximately 89% on the validation dataset.
