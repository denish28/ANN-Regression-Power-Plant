# ANN Regression for Power Plant Energy Prediction

## 📌 Project Overview

This project uses an Artificial Neural Network (ANN) built with PyTorch to predict power plant energy output using input features such as temperature, vacuum, pressure, and relative humidity.

## 🎯 Objectives

* Build an ANN regression model using PyTorch.
* Train a neural network to predict energy output.
* Evaluate the model using regression metrics.
* Visualize training and validation loss.

## 🛠️ Technologies Used

* Python
* PyTorch
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Jupyter Notebook

## 📊 Dataset

The dataset contains environmental measurements used to predict power plant energy output.

Features:

* **AT:** Temperature
* **V:** Vacuum
* **AP:** Pressure
* **RH:** Relative Humidity

Target:

* **PE:** Power output

The notebook expects a dataset file named `powerplant_data.csv`. Add the dataset to the repository only if you have permission to redistribute it.

## 🧠 ANN Architecture

The neural network consists of:

* Input layer
* First hidden layer with 6 neurons and ReLU activation
* Second hidden layer with 6 neurons and ReLU activation
* Output layer with 1 neuron

## ⚙️ Project Workflow

1. Load the dataset.
2. Preprocess the data.
3. Split the data into training and testing sets.
4. Scale the input features.
5. Convert the data into PyTorch tensors.
6. Build the ANN model.
7. Train the model.
8. Evaluate predictions.
9. Visualize model performance.

## 📈 Evaluation Metrics

* Mean Squared Error (MSE)
* R² Score

Add your actual evaluation results after running the notebook.

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/ANN-Regression-Power-Plant.git
```

### 2. Install dependencies

```bash
pip install torch pandas numpy scikit-learn matplotlib jupyter
```

### 3. Open Jupyter Notebook

```bash
jupyter notebook
```

Open `ANN_regression.ipynb` and execute the cells in order.

Ensure that `powerplant_data.csv` is available in the project directory.

## 🔮 Future Improvements

* Experiment with different ANN architectures.
* Tune hyperparameters.
* Compare ANN with traditional regression models.
* Improve prediction performance.

## 👨‍💻 Author

**Your Name**

MCA Student | Machine Learning | Deep Learning | Python
