# Convolutional Neural Networks (CNNs) with FastAI 🖼️🤖

This project demonstrates the use of **Convolutional Neural Networks (CNNs)** for image classification using the **FastAI** library. The goal is to classify images from the MNIST dataset and explore the inner workings of CNNs. 🎯📊

---

## Table of Contents 📑
1. [Overview](#overview-)
2. [Installation](#installation-)
3. [Usage](#usage-)
4. [Code Structure](#code-structure-)
5. [Results](#results-)
6. [License](#license-)

---

## Overview 🚀

This project:
- Uses **FastAI** to build and train a CNN for image classification. 🤖📸
- Explores the use of convolutional layers, activation functions, and batch normalization. 🧠🔍
- Visualizes the training process, layer statistics, and model performance. 📊📉

---

## Installation 🛠️

To run this project, you need to install the required libraries. Run the following commands:

```bash
!pip install fastai
!pip install torch torchvision
!pip install pandas matplotlib
```

---

## Usage 🖥️

1. **Load Dataset**: The script loads the MNIST dataset using FastAI's data block API.
2. **Build CNN**: A simple CNN is defined using convolutional layers, ReLU activations, and batch normalization.
3. **Train Model**: The model is trained using the `Learner` class and the `fit_one_cycle` method.
4. **Visualize Results**: Training statistics, layer activations, and model performance are visualized.

---

## Code Structure 🗂️

- **Data Preparation**:
  - Loads the MNIST dataset and prepares it for training.
  - Defines data loaders and transformations.

- **Model Definition**:
  - Defines a simple CNN with convolutional layers, batch normalization, and ReLU activations.
  - Uses the `sequential` function to stack layers.

- **Training**:
  - Trains the CNN using the `Learner` class and the `fit_one_cycle` method.
  - Tracks training metrics and activation statistics.

- **Visualization**:
  - Plots training schedules, layer statistics, and activation histograms.

---

## Results 📊

- **Training Accuracy**: The model achieves high accuracy on the MNIST dataset.
- **Layer Statistics**: Visualizations provide insights into the behavior of convolutional layers and activations.
- **Training Schedule**: The learning rate schedule is plotted to show how it changes during training.

---

## License 📜

This project is licensed under the **MIT License**. Feel free to use, modify, and distribute it as needed.

---

## Example Output 🖼️

Here’s an example of the model's training progress:

```plaintext
Epoch 1: train_loss=0.123, val_loss=0.045, accuracy=0.987
Epoch 2: train_loss=0.045, val_loss=0.032, accuracy=0.991
```

---

## Dependencies 📦

- `fastai`
- `torch`
- `torchvision`
- `pandas`
- `matplotlib`

---

## Author 👨‍💻

This project was created by **[Navid Falah](https://github.com/navidfalah)**. Feel free to reach out for questions or collaborations at **navid.falah7@gmail.com**! 🤝
