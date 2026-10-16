# ANN in Healthcare: Heart Disease Detection

## Project Overview
This project was developed for the Machine Learning course (**SAIA 2133**) at **Universiti Teknologi Malaysia (UTM)**. 

The project aims to predict the presence of heart disease using an Artificial Neural Network (ANN) trained on clinical patient data. It demonstrates how deep learning can identify patterns associated with heart disease and support early detection research.

---

## Dataset
* **Source:** UCI Heart Disease Dataset
* **Task:** Binary Classification (Heart Disease / No Heart Disease)
* **Input:** Patient clinical features
* **Output:** Predicted heart disease status

---

## Methodology

### 1. Data Preprocessing
* Performed data cleaning and exploratory data analysis (EDA).
* Applied feature scaling and one-hot encoding.
* Split the dataset into training and testing sets.

### 2. Model Development
* Developed a Multilayer Perceptron (MLP) using TensorFlow/Keras.
* Implemented three hidden layers with dropout, batch normalization, and L2 regularization to reduce overfitting.

### 3. Model Evaluation
* Evaluated model performance using accuracy, precision, recall, F1-score, and a confusion matrix.

---

## Results
The ANN achieved **95.56% test accuracy**, correctly predicting 43 out of 45 patient records.

| Metric | Result |
| :--- | :--- |
| **Test Accuracy** | 95.56% |
| **Correct Predictions** | 43 / 45 |
| **Incorrect Predictions** | 2 / 45 |

The results demonstrate the potential of neural networks for heart disease classification, although further validation with larger datasets is necessary before real-world clinical applications.

---

## Technologies Used
* **Python**
* **TensorFlow / Keras**
* **Scikit-learn**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Jupyter Notebook**

---

## Future Improvements
* Train and evaluate the model on larger, more diverse datasets.
* Perform hyperparameter tuning to improve generalization.
* Explore Explainable AI (XAI) techniques to improve model interpretability.

---

## Disclaimer
> This project was developed for academic purposes and is not intended for clinical diagnosis or medical decision-making.
