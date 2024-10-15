
# MNIST Image Classification with Convolutional Neural Networks (CNN)

This project implements an image classification model using a Convolutional Neural Network (CNN) to classify handwritten digits from the MNIST dataset. The code includes model building, training, evaluation, and visualization.


## Project Overview

The project utilizes the MNIST dataset to build a CNN-based image classifier. Key steps include:

- Loading and preprocessing the MNIST data.
- Building a CNN model with TensorFlow/Keras.
- Training the model on the training dataset.
- Evaluating model performance using classification reports and confusion matrix.
- Visualizing predictions and loss using Matplotlib.  

## Features

- **CNN Architecture**: The network includes convolutional layers for feature extraction and fully connected layers for classification.
- **Model Evaluation**: The model is evaluated with performance metrics like accuracy, confusion matrix, and classification report.
- **Visualizations**: Displays random predictions and training loss using Matplotlib.
## How to Run the Project 

1. Clone this repository:
```bash
git clone https://github.com/Codder-lab/CNN_Image_Classification.git
cd CNN_Image_Classification
```

2. Install the required dependencies:
```bash
pip install -r requirements.txt
```
## Results

- The model achieves a high test accuracy on the MNIST dataset.
- Misclassifications are highlighted for further analysis.
- The training process and loss curves help in diagnosing the model's behavior over epochs.

## Conclusion

This project showcases the use of CNNs for image classification using the MNIST dataset. Hyperparameters like the number of filters, layer sizes, and dropout can be tuned to optimize model performance.

