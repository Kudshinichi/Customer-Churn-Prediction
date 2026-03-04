Customer Churn Prediction using ANN

📌 Project Overview
This project aims to predict whether a bank customer will leave (churn) or stay, based on various demographic and financial factors. By using an Artificial Neural Network (ANN), the model identifies non-linear patterns in customer behavior to provide high-accuracy predictions.


📊 Dataset
The dataset customer_churn.csv includes 10,000 records with the following key features:

Credit Score

Geography & Gender

Age & Tenure

Balance & Number of Products

Estimated Salary

Exited (Target Variable): 1 if the customer left, 0 if they stayed.


🛠️ Tech Stack
Language: Python

Deep Learning: TensorFlow / Keras

Data Manipulation: Pandas, NumPy

Visualization: Matplotlib, Seaborn

Preprocessing: Scikit-Learn (Label Encoding, One-Hot Encoding, Feature Scaling)


🧠 Model Architecture
The ANN is structured with the following layers:

Input Layer: Handles the preprocessed features.

Hidden Layers: Fully connected layers with ReLU activation functions.

Output Layer: A single neuron with a Sigmoid activation function to output the probability of churn.

Optimizer: Adam

Loss Function: Binary Crossentropy

📈 Results
The model achieved an accuracy of approximately [Insert Your Accuracy]% on the test set.

Visualizations in the notebook include the Confusion Matrix and Training/Validation Accuracy curves.
