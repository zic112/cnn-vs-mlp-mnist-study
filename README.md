# MNIST CNN Experiments (PyTorch)

This repository contains experiments on the MNIST dataset using PyTorch. The project focuses on building, training, and evaluating neural network models for handwritten digit classification.

---

## 📌 Overview

The objective of this project is to:
- Implement a Convolutional Neural Network (CNN) for image classification
- Train and evaluate the model on MNIST dataset
- Analyze performance using accuracy and loss metrics
- Visualize training behavior and learned features

---

## 🧠 Model Architecture

The model consists of:
- Convolutional layers for feature extraction
- ReLU activation functions
- Max pooling layers for dimensionality reduction
- Fully connected layers for classification

---

## ⚙️ Features

- PyTorch-based implementation
- Training and validation workflow
- Accuracy and loss tracking
- Visualization of:
  - Training vs validation curves
  - Model predictions
  - Learned filters (CNN)

---

## 📊 Dataset

**MNIST Dataset**
- 60,000 training images
- 10,000 test images
- Grayscale images of handwritten digits (0–9)

---

## 🚀 Training Details

| Parameter        | Value        |
|-----------------|-------------|
| Batch Size      | 64          |
| Learning Rate   | 0.001       |
| Epochs          | 10          |
| Optimizer       | Adam        |
| Loss Function   | CrossEntropyLoss |

---

## 📈 Results

- High classification accuracy on test data
- Smooth convergence during training
- Minimal overfitting observed

---

## 🖼️ Visualizations

The project includes:
- Training vs validation loss curves
- Training vs validation accuracy curves
- Sample predictions vs actual labels
- Visualization of CNN filters

---

## 📂 Project Structure

```
.
├── Notebook.ipynb     # Main notebook
├── data/              # Dataset (auto-downloaded)
└── README.md
```

---

## ▶️ How to Run

### 1. Clone the repository
```bash
git clone https://github.com/your-username/cnn-vs-mlp-mnist-study.git
cd cnn-vs-mlp-mnist-study
```

### 2. Install dependencies
```bash
pip install torch torchvision matplotlib numpy
```

### 3. Run the notebook
```bash
jupyter notebook
```

---

## 🔍 Key Learnings

- Understanding CNNs for image classification
- Building training pipelines in PyTorch
- Evaluating model performance
- Visualizing neural network behavior

---

## 📌 Future Improvements

- Add MLP baseline comparison
- Hyperparameter tuning
- Add dropout and batch normalization
- Extend to datasets like CIFAR-10
- Convert notebook into modular scripts

---

## 🤝 Contributing

Contributions are welcome. Feel free to fork the repo and submit a pull request.

---

## 📜 License

This project is open-source.
