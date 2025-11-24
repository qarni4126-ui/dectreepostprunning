Decision Tree Classifier with Post-Pruning on Breast Cancer Dataset

This project implements a Decision Tree Classifier with post-pruning (cost-complexity pruning) using the Breast Cancer Wisconsin dataset available in scikit-learn.
The goal is to demonstrate how pruning helps reduce overfitting and improves generalization performance.

📌 Project Overview

Decision trees tend to overfit when grown without constraints.
To address this, cost-complexity pruning (a post-pruning technique) is applied to simplify the model after it has fully grown.

This repository includes:

Training of a baseline decision tree

Extraction of pruning path (ccp_alphas)

Model selection based on validation accuracy

Visualization of model performance

🧰 Technologies Used

Python

scikit-learn

NumPy

Matplotlib

📂 Dataset

The Breast Cancer Wisconsin dataset is a built-in dataset in scikit-learn that contains features computed from digitized images of fine-needle aspirate of breast masses.
It is a binary classification problem: malignant vs. benign.
