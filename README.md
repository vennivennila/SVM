# 🧠 Support Vector Machine (SVM) Classifier - Jupyter Notebook

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-Model-orange.svg)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen.svg)

This repository contains a beginner-friendly Jupyter Notebook that demonstrates the **Support Vector Machine (SVM)** algorithm using Python and `scikit-learn`. The notebook covers model training, prediction, and evaluation with step-by-step explanations.

---

## 📌 Project Highlights

- 📂 Dataset loading and preprocessing
- 🧠 Applying the SVM model for classification
- 📊 Model evaluation using accuracy, confusion matrix, and classification report
- 📈 (Optional) Visualizing decision boundaries
- 🔁 Hyperparameter tuning (e.g. kernel type, C, gamma)

---

## 🔍 How SVM Works

SVM is a supervised learning algorithm used to classify data by finding the **best separating boundary (hyperplane)**.

### 🟦 What is a Hyperplane?

A **hyperplane** is the line or surface that separates different classes:

- In 2D, it’s a straight line.
- In 3D, it’s a flat plane.
- In higher dimensions, it's called a hyperplane.

### 🟩 What is a Margin?

The **margin** is the distance between the hyperplane and the closest data points from each class. SVM tries to **maximize this margin** for better performance.

### 🟥 What are Support Vectors?

**Support vectors** are the data points closest to the hyperplane. These points determine the position and angle of the hyperplane.

### 🌐 What is a Kernel?

When data is **not linearly separable**, SVM uses a **kernel function** to transform it into a higher-dimensional space where it becomes separable.

**Common kernels**:
- `linear`: For simple linearly separable data
- `rbf`: Default, used for nonlinear boundaries
- `poly`: Polynomial decision boundaries
- `sigmoid`: Acts like a neural network

---

## 🛠️ Technologies Used

| Tool             | Description                        |
|------------------|------------------------------------|
| Python           | Programming language               |
| Jupyter Notebook | Interactive environment            |
| scikit-learn     | Machine learning library           |
| Pandas           | Data manipulation                  |
| Matplotlib       | Visualization                      |

