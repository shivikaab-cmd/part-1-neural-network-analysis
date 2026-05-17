# Neural Network Fundamentals and Training Behavior Analysis

## Project Overview

This project focuses on building and evaluating a neural network model for customer churn prediction using TensorFlow and Keras.

The notebook demonstrates the complete machine learning workflow including:
- Data loading and exploration
- Data preprocessing
- Feature scaling
- Neural network creation
- Model training
- Evaluation and visualization
- Hyperparameter experimentation
- Performance interpretation

The objective is to understand neural network fundamentals and analyze training behavior using a structured business dataset.

---

# Dataset Description

The dataset contains customer-related information such as:
- Demographics
- Subscription plans
- Contract details
- Usage behavior
- Payment methods
- Churn status

The target variable is:
- `churn`

The goal is to predict whether a customer is likely to churn or remain with the service.

---

# Technologies and Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow / Keras

---

# Project Workflow

## 1. Data Exploration

The dataset was explored to understand:
- Dataset shape
- Data types
- Missing values
- Statistical summaries
- Target variable distribution

---

## 2. Data Preprocessing

The preprocessing steps included:
- Removal of unnecessary columns
- Label encoding of categorical variables
- Feature scaling using StandardScaler
- Train-test split

These steps improve neural network training efficiency and model performance.

---

## 3. Neural Network Architecture

A feed-forward neural network was created with:
- Input layer
- Two hidden layers using ReLU activation
- Output layer using sigmoid activation

The model was compiled using:
- Adam optimizer
- Binary crossentropy loss
- Accuracy metric

---

## 4. Model Training

The model was trained using:
- 30 epochs
- Batch size of 32
- Validation split for monitoring performance

Training and validation curves were generated to analyze model learning behavior.

---

## 5. Model Evaluation

The model was evaluated using:
- Accuracy score
- Confusion matrix
- Classification report

These metrics help assess classification performance and model generalization.

---

## 6. Hyperparameter Experimentation

Different configurations were analyzed to study the impact of:
- Number of neurons
- Learning rate
- Hidden layer architecture

The experiments demonstrated how hyperparameters influence neural network performance.

---

# Results

The neural network achieved good classification performance on the customer churn dataset.

Key observations:
- Validation accuracy improved steadily during training
- Loss decreased consistently across epochs
- The model successfully identified churn patterns
- Proper preprocessing improved convergence and stability

---

# Output Visualizations

The following visualizations were generated:
- Churn distribution plot
- Accuracy curve
- Loss curve
- Confusion matrix

All visualizations are stored inside the `results` folder.

---

# Folder Structure

```text
part-1-neural-network-analysis/
│
├── README.md
├── notebook.ipynb
├── requirements.txt
└── results/
    ├── model_comparison_table.png or .csv
    └── evaluation_outputs.png
