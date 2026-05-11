# 🧠 Handwritten Digit Recognition using PyTorch

A deep learning project that trains a Neural Network on the famous MNIST handwritten digit dataset using PyTorch.  
This project demonstrates the complete workflow of building, training, and evaluating a neural network for image classification.

---

# 📌 Project Overview

The MNIST dataset contains grayscale images of handwritten digits (0–9).  
The goal of this project is to train a neural network capable of accurately recognizing and classifying these digits.

This notebook covers:

- Loading and preprocessing image data
- Building a feedforward neural network
- Forward propagation
- Applying activation functions
- Training with backpropagation
- Optimizing using gradient descent
- Evaluating model accuracy

---

# 🖼️ Dataset

## MNIST Dataset
The MNIST dataset consists of:

- **60,000** training images
- **10,000** testing images
- Image size: **28 × 28 pixels**
- Total classes: **10 digits (0–9)**

Each image is flattened into a vector before being passed into the neural network.

---

# 🛠️ Technologies Used

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Jupyter Notebook

---

# 🧩 Neural Network Architecture

The implemented neural network consists of:

| Layer | Description |
|---|---|
| Input Layer | 784 neurons (28×28 image flattened) |
| Hidden Layer | Fully connected dense layer |
| Activation Function | ReLU |
| Output Layer | 10 neurons (digits 0–9) |

---

# ⚙️ Working Process

## 1️⃣ Data Loading
The MNIST dataset is downloaded using `torchvision.datasets`.

## 2️⃣ Data Preprocessing
Images are:
- Converted to tensors
- Normalized
- Flattened into vectors

## 3️⃣ Model Creation
A custom neural network is created using:

```python
nn.Linear()
```

and activation functions from:

```python
torch.nn.functional
```

---

## 4️⃣ Training
The model is trained using:

- Forward propagation
- Loss calculation
- Backpropagation
- Weight optimization

---

## 5️⃣ Evaluation
After training, the model predicts handwritten digits and calculates accuracy on test data.

---

# 📂 Project Structure

```bash
├── Pytorch_Neural_Network_Implementation.ipynb
├── README.md
```

---

# 🚀 Installation

## Clone the Repository

```bash
git clone https://github.com/your-username/your-repository-name.git
```

## Navigate to Project Folder

```bash
cd your-repository-name
```

## Install Dependencies

```bash
pip install torch torchvision matplotlib numpy
```

---

# ▶️ Running the Notebook

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```bash
Pytorch_Neural_Network_Implementation.ipynb
```

Run all cells to train and test the neural network.

---

# 📊 Features

✅ MNIST handwritten digit classification  
✅ Neural network built from scratch using PyTorch  
✅ Data preprocessing and normalization  
✅ Model training and optimization  
✅ Accuracy evaluation  
✅ Beginner-friendly implementation  

---

# 🧪 Sample Workflow

```text
Input Image → Flattening → Neural Network → Prediction → Digit Output
```

---

# 📈 Learning Outcomes

Through this project, you can learn:

- Basics of Deep Learning
- Neural Networks in PyTorch
- Forward and Backward Propagation
- Loss Functions
- Optimizers
- Image Classification
- Tensor Operations

---

# 🔥 Future Improvements

- Add Convolutional Neural Networks (CNN)
- Improve model accuracy
- Add GUI for digit prediction
- Deploy as a web application
- Save and load trained models

---

# 🤝 Contributing

Contributions are welcome!

Feel free to:
- Fork the repository
- Improve the model
- Add new features
- Create pull requests

---

# 📜 License

This project is open-source and available under the MIT License.

---

# 👨‍💻 Author

**Kartik Jadhav**

Deep Learning & AI Enthusiast 🚀

---
