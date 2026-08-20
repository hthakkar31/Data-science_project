Neural Network & Hyperparameter Tuning

📌 Project Overview

This project explores binary classification and image classification using deep learning. It begins with the UCI Bank Marketing dataset for predicting customer subscription outcomes, then extends to a Convolutional Neural Network (CNN) on the CIFAR‑10 dataset.

⚙️ Tech Stack
Python

Libraries:

NumPy, Pandas – data manipulation

Matplotlib, Seaborn – visualization

Scikit-learn – preprocessing, train/test split

TensorFlow/Keras – deep learning models

Keras Tuner – hyperparameter optimization

📂 Dataset
1. UCI Bank Marketing Dataset
Rows: 45,211

Features: 17 (categorical + numerical)

Target: y → renamed to target (binary: yes/no)

Preprocessing includes:

Dropping high‑null columns (poutcome, contact)

One‑Hot Encoding categorical variables

Standardizing numerical features

2. CIFAR‑10 Dataset
Images: 60,000 (32×32 color images)

Classes: 10 categories (airplane, car, bird, cat, deer, dog, frog, horse, ship, truck)

Preprocessing: normalization (0–1 range), one‑hot encoding of labels

🔄 Workflow
Data Preprocessing

Handle missing values

Encode categorical variables

Scale numerical features

Model Architecture (Bank Dataset)

Input layer (44 features after preprocessing)

Dense layer (32 neurons, tanh)

Dropout (20%)

Output layer (sigmoid for binary classification)

Training & Evaluation

Optimizers: Adam & SGD (with momentum, Nesterov)

Loss: Binary Crossentropy

Metrics: Accuracy

Achieved ~89–90% validation accuracy

Hyperparameter Tuning (Keras Tuner)

Tunable units in Dense layers (16–256, 12–120)

Tunable learning rate (0.01, 0.001, 0.0001)

Best hyperparameters:

Units 1: 176

Units 2: 36

Learning Rate: 0.001

CNN on CIFAR‑10

Convolutional layers for feature extraction

Pooling layers for dimensionality reduction

Dense layers for classification

Output: 10 classes with softmax activation

📊 Visualizations
Accuracy & loss curves (training vs validation)

Confusion matrix for predictions on test data

CIFAR‑10 sample images
