# Banknote Authentication using Single Layer Perceptron

## Project Overview

This project implements a **Single Layer Perceptron from scratch using NumPy** to classify banknotes as **authentic** or **forged**. The model is trained on the **UCI Banknote Authentication Dataset** and evaluated using standard machine learning metrics.

The project also includes Exploratory Data Analysis (EDA), data preprocessing, visualization of the learning process, and comparison with Scikit-learn's Perceptron implementation.

---

## Dataset

**Dataset:** Banknote Authentication Dataset

**Source:**
https://archive.ics.uci.edu/ml/datasets/banknote+authentication

### Features

- Variance
- Skewness
- Curtosis
- Entropy

### Target

- **0** → Authentic Banknote
- **1** → Forged Banknote

---

## Project Workflow

1. Load Dataset
2. Explore Dataset
3. Perform Exploratory Data Analysis (EDA)
4. Preprocess Data
5. Implement Single Layer Perceptron from Scratch
6. Train the Model
7. Evaluate Performance
8. Compare with Scikit-learn Perceptron

---

## Exploratory Data Analysis

The following visualizations are included:

- Histograms
- Correlation Heatmap
- Scatter Plot
- Boxplots

These plots help understand the feature distributions, correlations, class separability, and outliers.

---

## Data Preprocessing

- Checked for missing values
- Standardized features using `StandardScaler`
- Split dataset into:
  - 80% Training
  - 20% Testing

---

## Perceptron Implementation

The perceptron is implemented **from scratch** using NumPy.

### Features

- Step Activation Function
- Weight Updates
- Bias Updates
- Error Tracking
- Weight History
- Bias History

---

## Model Evaluation

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## Learning Visualizations

The project includes the following learning plots:

- Training Error vs Epoch
- Weight Evolution
- Bias Evolution
- Learning Rate Comparison

---

## Libraries Used

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## Project Structure

```
Banknote-Authentication/
│
├── banknote_authentication.csv
├── banknote_authentication.ipynb
├── banknote_authentication.py
├── requirements.txt
├── README.md
└── images/ (optional)
```

---

## Installation

Clone the repository

```bash
git clone https://github.com/your-username/Banknote-Authentication.git
```

Move into the project directory

```bash
cd Banknote-Authentication
```

Install the required libraries

```bash
pip install -r requirements.txt
```

Run the project

```bash
python banknote_authentication.py
```

or open

```
banknote_authentication.ipynb
```

using Jupyter Notebook.

---

## Results

The custom Single Layer Perceptron successfully classifies banknotes into authentic and forged categories with high accuracy. The training error decreases over epochs, and the weight and bias values converge, demonstrating effective learning.

---

## Comparison with Scikit-learn

The project also compares the custom implementation with Scikit-learn's built-in `Perceptron` classifier to validate the correctness of the implementation.

---

## Future Improvements

- Multi-Layer Perceptron (MLP)
- Different activation functions
- Hyperparameter tuning
- Decision boundary visualization
- Cross-validation
