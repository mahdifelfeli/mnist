# MNIST Handwritten Digit Classification ✍️

A simple Artificial Neural Network (ANN), also known as a Multi-Layer Perceptron (MLP), built with TensorFlow/Keras to classify handwritten digits from the classic MNIST dataset.



---

## Overview

This project implements a basic neural network to recognize digits from 0 to 9. The model is trained on the MNIST dataset, which contains 60,000 training images and 10,000 testing images of 28x28 grayscale handwritten digits.

### Performance
The model achieves an accuracy of approximately **~97.6%** on the test set.

---

## Tech Stack

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3776AB?style=for-the-badge&logo=matplotlib&logoColor=white)

---

## Model Architecture

The model is a simple sequential ANN:

1.  **Flatten Layer:** Converts the 28x28 pixel images into a 1D array (784 neurons).
2.  **Dense Layer:** A fully connected hidden layer with 128 neurons and **ReLU** activation.
3.  **Dense Layer (Output):** The output layer with 10 neurons (one for each digit, 0-9) and **Softmax** activation to provide class probabilities.

---

## How to Use

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/mahdifelfeli/mnist.git](https://github.com/mahdifelfeli/mnist.git)
    cd mnist
    ```

2.  **Create a virtual environment and install dependencies:**
    ```bash
    # Create environment
    python -m venv venv
    # Activate (Windows)
    .\venv\Scripts\activate
    # Activate (macOS/Linux)
    source venv/bin/activate
    
    # Install libraries
    pip install -r requirements.txt
    ```

3.  **Run the Notebook:**
    * The MNIST dataset is downloaded automatically by Keras the first time you run the code.
    * Open and run the `mnist_classification.ipynb` notebook using Jupyter:
    ```bash
    jupyter notebook
    ```
