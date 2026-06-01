# MNIST Digit Classification using TensorFlow

A simple deep learning project that classifies handwritten digits (0–9) using the MNIST dataset.

The model is built using TensorFlow/Keras and consists of a fully connected neural network trained on 60,000 handwritten digit images and evaluated on 10,000 test images.

## Features

* Data preprocessing and normalization
* Neural network built with TensorFlow/Keras
* Training with validation split
* Accuracy and loss visualization
* Prediction on individual handwritten digit images
* Evaluation using test set accuracy

## Dataset

This project uses the MNIST dataset, which contains:

* 60,000 training images
* 10,000 testing images
* Grayscale images of size 28 × 28
* Digits from 0 to 9

## Model Architecture

Input (28×28 Image)
→ Flatten Layer
→ Dense Layer (128 neurons, ReLU)
→ Dense Layer (10 neurons, Softmax)

## Training

* Optimizer: Adam
* Loss Function: Sparse Categorical Crossentropy
* Epochs: 10
* Validation Split: 20%

## Results

The model achieves high classification accuracy on the MNIST test dataset and is able to correctly predict handwritten digits that were not seen during training.

## Visualizations

The notebook includes:

* Training vs Validation Loss
* Training vs Validation Accuracy
* Sample digit predictions

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Scikit-learn

## Running the Project

1. Clone the repository

```bash
git clone <repository-url>
```

2. Install dependencies

```bash
pip install tensorflow numpy matplotlib scikit-learn
```

3. Run the notebook

```bash
jupyter notebook mnist_digit_classification.ipynb
```

## What I Learned

This project helped me understand:

* Data preprocessing for image datasets
* Neural network architecture design
* Model training and evaluation
* Overfitting and validation metrics
* Making predictions with trained models

---

A beginner deep learning project built while learning TensorFlow and neural networks.
