# 🧠 MNIST Neural Network From Scratch with Hyperparameter Optimization
![Python](https://img.shields.io/badge/Python-3.x-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-DeepLearning-orange)
![NumPy](https://img.shields.io/badge/NumPy-NumericalComputing-blue)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-green)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

This project implements a **Neural Network from scratch using NumPy** to classify handwritten digits from the **MNIST dataset**.

The project also includes **Hyperparameter Optimization using Genetic Algorithm and Random Search**, along with a comparison against a **built-in TensorFlow/Keras neural network model**.

Additionally, **VGG16 (pre-trained CNN)** is used for **feature extraction** to improve the quality of input features before training the neural network.

---

# 🚀 Project Features

* Neural Network implemented **from scratch using NumPy**
* Forward propagation and **Backpropagation algorithm**
* Multiple activation functions:

  * ReLU
  * Sigmoid
  * Tanh
* Softmax output layer for multi-class classification
* Cross-entropy loss function
* Mini-batch Gradient Descent

### Hyperparameter Optimization

Two optimization methods are implemented:

* **Genetic Algorithm**
* **Random Search**

These methods search for the best configuration of:

* Number of hidden layers
* Number of neurons
* Activation function
* Learning rate
* Batch size
* Number of epochs

---

# 🧩 Feature Extraction using VGG16

Instead of using raw pixel values directly, the project uses a **pre-trained VGG16 Convolutional Neural Network** for feature extraction.

Steps:

1. Resize MNIST images from **28×28 → 32×32**
2. Convert grayscale images to **RGB**
3. Apply **VGG16 preprocessing**
4. Extract deep features using VGG16
5. Flatten features for the neural network input

This improves the representation of the data before training.

---

# 🧠 From-Scratch Neural Network

The neural network implemented in this project includes:

* Custom weight initialization
* Forward propagation
* Backpropagation
* Gradient descent updates
* Mini-batch training

The architecture supports:

* Multiple hidden layers
* Configurable number of neurons
* Different activation functions

---

# 🤖 Built-in Model (TensorFlow / Keras)

A second model is implemented using **TensorFlow/Keras** to compare results with the from-scratch implementation.

Architecture:

Input Layer
Hidden Layers (user-defined)
Softmax Output Layer

Optimizer used:

Adam Optimizer

Loss Function:

Categorical Cross-Entropy

---

# ⚙️ Hyperparameter Optimization

## Genetic Algorithm

The Genetic Algorithm evolves a population of configurations using:

* Selection
* Crossover
* Mutation

Each individual represents a neural network configuration, and the fitness is measured using **validation accuracy**.

---

## Random Search

Random Search randomly samples configurations from the hyperparameter space and evaluates their performance.

It is a simple yet effective method for hyperparameter tuning.

---

# 📊 Evaluation Metrics

The models are evaluated using:

* Accuracy
* Classification Report
* Confusion Matrix
* Training Loss
* Validation Loss
* Training Accuracy
* Validation Accuracy

The project also plots **training and validation curves** to visualize learning performance.

---

# 📊 Dataset

Dataset used:

**MNIST Handwritten Digits Dataset**

Dataset details:

* 60,000 training images
* 10,000 test images
* 10 classes (digits 0–9)
* Image size: 28×28 pixels

---

# 🛠️ Technologies Used

Python Libraries:

* NumPy
* TensorFlow / Keras
* Scikit-learn
* Matplotlib

Deep Learning Model:

* VGG16 (Pre-trained CNN)

---

# 📈 Results

This project compares two approaches:

| Model                       | Description                        |
| --------------------------- | ---------------------------------- |
| Neural Network from Scratch | Implemented manually using NumPy   |
| Keras Model                 | Implemented using TensorFlow/Keras |

Both models are evaluated on the **MNIST test dataset**.

The comparison highlights the differences between **manual neural network implementation and modern deep learning frameworks**.

---

# ▶️ How to Run

### 1. Install dependencies

pip install numpy tensorflow scikit-learn matplotlib

### 2. Run the program

python main.py

### 3. Choose optimization method

1 → Genetic Algorithm
2 → Random Search

---

# 📈 Training Visualization

The program automatically plots:

* Training Loss
* Validation Loss
* Training Accuracy
* Validation Accuracy

These plots help understand **model convergence and performance**.

---

# 🎯 Learning Outcomes

This project demonstrates:

* How neural networks work internally
* Implementing backpropagation from scratch
* Hyperparameter optimization techniques
* Feature extraction using CNNs
* Comparing custom models with deep learning frameworks

---

# 👨‍💻 Author

Mohamed Esam
Computer Science Student – Cairo University

Interests:

* Data Science
* Machine Learning
* Artificial Intelligence

GitHub:
https://github.com/Mohamedesam122

LinkedIn:
https://www.linkedin.com/in/mohamed-esam-354638292

