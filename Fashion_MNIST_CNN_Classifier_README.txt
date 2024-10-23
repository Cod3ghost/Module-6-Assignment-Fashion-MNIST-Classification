
Fashion MNIST Classification with CNN

This project demonstrates image classification using a Convolutional Neural Network (CNN) on the Fashion MNIST dataset. The dataset consists of 60,000 training and 10,000 test grayscale images of 10 clothing categories.

Project Overview

The CNN model is built using Keras and TensorFlow, with layers designed to extract features from images and classify them into one of 10 fashion categories. The dataset is preprocessed, normalized, and reshaped before being fed into the model.

Requirements

- Python 3.x
- TensorFlow 2.x (includes Keras)
- NumPy
- Matplotlib

Install Dependencies

pip install tensorflow numpy matplotlib

How to Run

1. Clone the repository and navigate to the directory:
   git clone https://github.com/your-repo/fashion-mnist-cnn.git
   cd fashion-mnist-cnn

2. Open Jupyter Notebook:
   jupyter notebook Fashion_MNIST_CNN_Classifier.ipynb

3. Run the notebook to execute all steps from loading data to predictions.

Data Preprocessing

- Reshaping: Convert the images to 28x28x1 (grayscale).
- Normalization: Scale pixel values from 0-255 to 0-1.
- One-Hot Encoding: Transform labels into vectors for classification.

Model Architecture

- 2 Convolutional layers (32, 64 filters)
- 2 Max-Pooling layers
- Fully connected (Dense) layer with 128 neurons
- Output layer with softmax for 10 classes

Results

The trained model achieves a reasonable accuracy on the test set, and predictions for test images are visualized in the notebook.
