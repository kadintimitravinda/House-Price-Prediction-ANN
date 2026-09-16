# House-Price-Prediction-ANN
House Price Prediction using Artificial Neural Network (ANN) with PyTorch, using area and main road access to predict house prices.
# 🏠 House Price Prediction using ANN

A Machine Learning project that predicts house prices using an Artificial Neural Network (ANN) built with PyTorch.

## 📌 Project Overview

This project focuses on predicting house prices based on selected housing features such as area and main road access.

An Artificial Neural Network is trained using a housing dataset to learn the relationship between input features and house prices. After training, the model is evaluated on test data and used to generate house price predictions.

## 🎯 Objectives

* Build a house price prediction model using ANN.
* Understand how neural networks learn from housing data.
* Apply data selection, train-test splitting, and tensor conversion.
* Train the model using PyTorch.
* Evaluate the model using Mean Squared Error (MSE).
* Predict the price of a new house.

## 📂 Dataset

The project uses a housing dataset containing 545 records and 3 columns.

### Dataset Features

| Feature        | Description                                      |
| -------------- | ------------------------------------------------ |
| `price`        | Target house price                               |
| `area`         | Area of the house                                |
| `mainroad=yes` | Indicates whether the house has main road access |

### Dataset Shape

* Rows: 545
* Columns: 3

## 🛠️ Technologies Used

* Python
* PyTorch
* Pandas
* Scikit-learn

## 🧠 Machine Learning Model

The project uses an Artificial Neural Network built using PyTorch.

### Model Architecture

```text
Input Layer
    ↓
2 Input Features
    ↓
Linear Layer: 2 → 16
    ↓
ReLU Activation
    ↓
Linear Layer: 16 → 8
    ↓
ReLU Activation
    ↓
Output Layer: 8 → 1
    ↓
Predicted House Price
```

### Model Configuration

* Input features: 2
* Hidden layer 1: 16 neurons
* Hidden layer 2: 8 neurons
* Output: 1 neuron
* Activation function: ReLU
* Loss function: Mean Squared Error (MSE)
* Optimizer: Adam
* Learning rate: 0.001
* Training epochs: 1000
* Test size: 20%

## 🔄 Project Workflow

1. Load the housing dataset.
2. Select input features and target price.
3. Split the data into training and testing sets.
4. Convert the data into PyTorch tensors.
5. Create the ANN model.
6. Define MSE loss and Adam optimizer.
7. Train the model for 1000 epochs.
8. Evaluate the model on test data.
9. Generate a house price prediction.

## 📁 Project Structure

```text
House-Price-Prediction-ANN/
│
├── Ann.ipynb
├── Housing-prepared.csv
└── README.md
```

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Install the required libraries

```bash
pip install pandas torch scikit-learn jupyter
```

### 3. Open the notebook

```bash
jupyter notebook Ann.ipynb
```

### 4. Run the notebook

Execute the cells in order to:

* Load the dataset.
* Train the ANN model.
* Test the model.
* Predict house prices.

## 📊 Model Evaluation

The model uses Mean Squared Error (MSE) to measure the difference between actual and predicted house prices.

The test loss is calculated after training using the test dataset.

> Note: The final model accuracy, test loss, and prediction performance should be added after running the notebook and checking the actual output.

## 🔮 Future Improvements

* Add more housing features such as bedrooms, bathrooms, parking, and furnishing status.
* Apply feature scaling for better neural network training.
* Compare ANN performance with Linear Regression and other ML models.
* Add MAE and R² evaluation metrics.
* Create a web application for house price prediction.
* Improve model performance using hyperparameter tuning.

## 👩‍💻 Author

**Mitra Kadinti**

AI & Data Science Student

GitHub: https://github.com/kadintimitravinda

---

⭐ If you find this project useful, consider giving it a star!
