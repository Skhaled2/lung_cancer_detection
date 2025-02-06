# lung_cancer_detection

This project focuses on detecting lung cancer using deep learning techniques. It utilizes the IQ-OTHNCCD lung cancer dataset, processes images, and trains a VGG16-based convolutional neural network (CNN) for classification into three categories:

Benign cases
Malignant cases
Normal cases
## Dataset
The dataset is structured as follows:

/The IQ-OTHNCCD lung cancer dataset/
│── Benign cases/
│── Malignant cases/
│── Normal cases/

## Dependencies
Ensure you have the following libraries installed before running the notebook:

pip install numpy opencv-python tensorflow scikit-learn matplotlib

## Features & Model Architecture

Pretrained Model: Uses VGG16 as a feature extractor.
Custom Layers: Fully connected layers added on top of the extracted features.
Optimizer: Adam optimizer.
Evaluation Metrics: Classification report, confusion matrix

## Steps to Run

Load Dataset: The script loads images, resizes them to 256x256, and assigns labels.
Preprocessing: Normalizes pixel values and encodes class labels.
Splitting Data: Splits into training and testing sets.
Model Training: Trains a CNN model based on VGG16.
Evaluation: Generates a classification report and confusion matrix.

## Results

The model's performance is evaluated using accuracy, precision, recall, and F1-score.


  
