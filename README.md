Breast Cancer Classification using Machine Learning and Neural Networks

link to the video: https://youtu.be/_GcdOiAHREg

Problem Statement
The goal of this project is to classify breast cancer tumors as either benign or malignant  using machine learning and neural network models. The dataset used is the Breast Cancer Wisconsin (Diagnostic) Dataset, which contains features computed from digitized images of breast mass samples.

Dataset
The dataset contains 569 samples with 30 features each, such as radius, texture, and symmetry. The target variable is the diagnosis (`M` for malignant and `B` for benign). (link: https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)


Findings(https://docs.google.com/document/d/1Gg3XuivTzq6HVHmGGlp17ALHq21yVTTxyPxL3Ix0MPM/edit?usp=sharing)


Instance
Optimizer
Regularizer
Epochs
Early Stopping
Dropout
Learning Rate
Accuracy
F1 Score
Precision
Recall
1
Adam
None
50
No
0.0
0.001
0.96
0.95
0.96
0.94
2
Adam
L2 (0.01)
50
Yes
0.0
0.001
0.97
0.96
0.97
0.95
3
RMSprop
L1 (0.01)
50
No
0.2
0.001
0.96
0.95
0.96
0.94
4
Adam
L2 (0.01)
50
Yes
0.2
0.001
0.97
0.96
0.97
0.95





Summary of Findings
1. Best Combination: Instance 4, which used the Adam optimizer, L2 regularization, dropout (0.2), and early stopping, achieved the highest accuracy (97%) and F1 score (0.96).
2. Comparison of ML and Neural Networks: The neural network models outperformed the XGBoost model (accuracy: 96%, F1 score: 0.95). The neural network's ability to learn complex patterns and the use of optimization techniques contributed to its superior performance.
3. XGBoost Hyperparameters: The XGBoost model was trained with the following hyperparameters:
   learning_rate: 0.1
   max_depth: 5
   n_estimators: 100

