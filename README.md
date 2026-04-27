# Handwritten Digit Classification

This project implements a Deep Learning model to recognize and classify handwritten digits (0-9). Utilizing the famous **MNIST dataset**, the project demonstrates the construction and training of an **Artificial Neural Network (ANN)** to achieve high-precision image recognition.

---

### ## Table of Contents
* [Overview](#overview)
* [Dataset](#dataset)
* [Technologies Used](#technologies-used)
* [Project Workflow](#project-workflow)
* [Installation and Usage](#installation-and-usage)
* [Results](#results)

---

### ## Overview
The goal of this project is to explore the capabilities of neural networks in computer vision. By processing 28x28 pixel grayscale images, the model learns to identify complex patterns in human handwriting, effectively mapping pixel intensity values to the correct numerical digit.

---

### ## Dataset
The project utilizes the **MNIST (Modified National Institute of Standards and Technology)** dataset:
* **Training Set:** 60,000 grayscale images of digits.
* **Testing Set:** 10,000 grayscale images for validation.
* **Format:** Each image is 28x28 pixels, representing a digit from 0 to 9.

---

### ## Technologies Used
The following technologies and frameworks are central to this implementation:
* **TensorFlow & Keras:** For building and training the Artificial Neural Network.
* **NumPy:** For efficient matrix manipulation and data handling.
* **Matplotlib:** For visualizing the digits and training progress.
* **OpenCV (Optional):** For potential image preprocessing and testing custom inputs.

---

### ## Project Workflow
1. **Data Loading:** Importing the MNIST dataset directly through Keras.
2. **Preprocessing:** Normalizing pixel values (scaling from 0–255 to 0–1) and flattening images for the input layer.
3. **Model Architecture:** Designing an ANN with multiple layers, including a **Dense** input layer, hidden layers with **ReLU** activation, and a **Softmax** output layer.
4. **Compilation:** Using the **Adam optimizer** and **Sparse Categorical Crossentropy** as the loss function.
5. **Training:** Fitting the model on the training data across several epochs.
6. **Prediction:** Testing the model on unseen data to verify accuracy.

---

### ## Installation and Usage
1. Clone the repository:
   ```bash
   git clone [https://github.com/yourusername/handwritten-digit-classification.git](https://github.com/yourusername/handwritten-digit-classification.git)
