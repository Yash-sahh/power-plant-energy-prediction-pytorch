# ⚡ Power Plant Energy Output Prediction using PyTorch ANN

A complete Deep Learning regression project that predicts the electrical energy output (PE) of a Combined Cycle Power Plant using a custom-built Artificial Neural Network (ANN) in PyTorch.

---

## 📌 Overview

This project demonstrates an end-to-end Deep Learning workflow using PyTorch, covering everything from preprocessing to model evaluation.

Instead of using high-level APIs, the ANN is implemented by subclassing `torch.nn.Module`, providing a deeper understanding of how neural networks are built in PyTorch.

---

## Problem Statement

Predict the electrical energy output (PE) of a Combined Cycle Power Plant using environmental variables such as:

- Temperature (AT)
- Ambient Pressure (AP)
- Relative Humidity (RH)
- Exhaust Vacuum (V)

This is a regression problem.

---

## Project Workflow

- Data preprocessing
- Train/Test Split
- Feature Scaling using StandardScaler
- Tensor Conversion
- TensorDataset & DataLoader
- Custom ANN implementation
- Training Loop
- Validation Loop
- Model Checkpoint Saving
- Model Loading
- Performance Evaluation
- Prediction Comparison

---

## Neural Network Architecture

Input Layer

↓

Hidden Layer (6 neurons + ReLU)

↓

Hidden Layer (6 neurons + ReLU)

↓

Output Layer (1 neuron)

---

## Technologies Used

- Python
- PyTorch
- NumPy
- Pandas
- Scikit-learn
- Matplotlib

---

## Results

Model Performance

- Training MSE ≈ 20.24
- Testing MSE ≈ 18.58
- R² Score ≈ 0.935

The trained ANN successfully learns the nonlinear relationship between environmental variables and electrical energy output.

---

## Repository Structure

```
Power-Plant-Energy-Prediction/
│
├── Power_Plant_Energy_Prediction_Using_PyTorch_ANN.ipynb
├── powerplant_data.csv
├── best_model.pt
├── requirements.txt
└── README.md
```

---

## Learning Outcomes

- Building ANN from scratch in PyTorch
- Working with nn.Module
- Forward & Backward Propagation
- DataLoader Pipeline
- Regression using Deep Learning
- Saving and Loading Models
- Model Evaluation

---

## Future Improvements

- Hyperparameter tuning
- Dropout & Batch Normalization
- Early Stopping
- TensorBoard Integration
- GPU Training
- Hyperparameter Optimization with Optuna

---

⭐ If you found this project useful, consider giving it a star.