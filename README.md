# Diabetes Classification using Multilayer Perceptron (MLP)

This project implements a **Multilayer Perceptron (MLP) neural network** to classify whether a patient has diabetes using the **Pima Indians Diabetes Dataset**.

The model is built using **Python and Scikit-learn** and demonstrates how neural networks can be applied to medical data for binary classification.

---

# Dataset

The dataset used is the **Pima Indians Diabetes Dataset**, which contains medical diagnostic measurements of patients.

### Features

| Feature | Description |
|------|------|
| Pregnancies | Number of pregnancies |
| Glucose | Plasma glucose concentration |
| BloodPressure | Diastolic blood pressure |
| SkinThickness | Triceps skin fold thickness |
| Insulin | 2-Hour serum insulin |
| BMI | Body Mass Index |
| DiabetesPedigreeFunction | Diabetes genetic influence |
| Age | Age of the patient |

### Target

| Value | Meaning |
|------|------|
| 0 | No Diabetes |
| 1 | Diabetes |

Dataset Source:  
https://raw.githubusercontent.com/jbrownlee/Datasets/master/pima-indians-diabetes.data.csv

---

# Model Used

The model used is a **Multilayer Perceptron (MLP) classifier**, which is a type of **feedforward artificial neural network**.

### Architecture

- Input Layer: 8 neurons (features)
- Hidden Layer 1: 8 neurons
- Hidden Layer 2: 8 neurons
- Output Layer: 1 neuron (binary classification)

### Activation Function

ReLU activation is used in hidden layers.

---

# Libraries Used

- Python
- NumPy
- Pandas
- Scikit-learn

---

# Workflow

1. Load the dataset
2. Split data into **features and target**
3. Perform **train-test split**
4. Apply **feature scaling using StandardScaler**
5. Train the **MLP classifier**
6. Make predictions on test data
7. Evaluate the model using **accuracy and classification report**

---

# Model Evaluation

The model performance is evaluated using:

- **Accuracy Score**
- **Precision**
- **Recall**
- **F1-score**

Example Output:
Accuracy: 0.77


Classification report includes:

- Precision
- Recall
- F1-score
- Support

---

# How to Run

Install required libraries:

```bash
pip install numpy pandas scikit-learn
```

Run the Python script:
python diabetes_mlp.py
