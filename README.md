# breast_Cancer_model

This project implements a simple feedforward neural network using PyTorch to classify breast masses as either Benign ('B') or Malignant ('M') based on features extracted from cell nuclei.

The dataset used in this project is the [Breast Cancer Wisconsin (Diagnostic) Dataset](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)), accessed directly from a public GitHub repository for convenience.

## Features

-   Loads data from a CSV file hosted online.
-   Performs data preprocessing including dropping columns, splitting data, and feature scaling.
-   Encodes target labels numerically.
-   Utilizes PyTorch `Dataset` and `DataLoader` for efficient data handling.
-   Implements a simple two-layer neural network.
-   Trains the network using Binary Cross Entropy Loss and SGD optimizer.
-   Evaluates the model's accuracy on a test set.

## Setup

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/rishu1947-ops/breast_Cancer_model
    cd breast-cancer-detection
    ```

2.  **Install dependencies:**
    It's recommended to use a virtual environment.
    ```bash
    pip install -r requirements.txt
    ```
    *Note: Ensure you have the correct PyTorch version installed. Refer to the [PyTorch website](https://pytorch.org/get-started/locally/) for detailed installation instructions.*

## Project Structure
