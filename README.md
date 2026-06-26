# Heart Disease Prediction & Classification Using Neural Networks

## Project Overview
This project, developed as a Bachelor's Graduation Project, focuses on building an end-to-end binary classification pipeline using Deep Learning to predict the risk of heart disease based on clinical and patient health attributes.

## Dataset Information
* **Dataset:** Clinical health attributes including age, sex, chest pain type (cp), cholesterol (chol), maximum heart rate achieved (thalach), and ST depression (oldpeak).
* **Preprocessing:** Handled missing values, filtered out invalid data placeholder tokens (`?`), and performed numeric conversion for complex categorical features.

## Model Architecture (Deep Learning)
Implemented a continuous dense neural network utilizing **Keras** and **TensorFlow** with the following layers:
* **Input Layer:** 13 key health dimensions.
* **Hidden Layers:** Rectified Linear Unit (ReLU) activation functions optimized with an Adam optimizer ($lr=0.001$) and cross-entropy loss.
* **Regularization:** Integrated Dropout layers to minimize overfitting during training epochs.
* **Output Layer:** Sigmoid activation function for binary fine/problem classification.

## Interactive Feature
* Features a dynamic prediction deployment block that evaluates single patient vectors and automatically invokes an integrated web response (Google Maps redirection to nearest cardiac hospitals) upon detecting positive cardiac risk criteria.

## Tools & Frameworks
* Python, Pandas & NumPy
* Keras & TensorFlow (Neural Networks)
* Scikit-Learn
* Jupyter Notebook
