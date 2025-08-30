🐱🐶 Cats vs Dogs Classification using SVM
📌 Task Overview

This project was developed as part of my Machine Learning Internship at SkillCraft Technologies.
The objective of this task was to build a machine learning model to classify cats vs dogs images using Support Vector Machine (SVM).

📂 Dataset

Dataset: Cats vs Dogs (Kaggle / provided in internship)

Total Images:

Training: 20,000 (10,000 cats, 10,000 dogs)

Validation: 5,000 (2,500 cats, 2,500 dogs)

Testing: 5,000 (2,500 cats, 2,500 dogs)

⚙️ Steps Involved

Data Preprocessing

Resized all images to 64x64

Flattened images → feature vectors of size 12288

Normalized pixel values

Dimensionality Reduction (PCA)

Reduced features to 300 components for faster training

Model Training

Used Support Vector Machine (SVM) with RBF kernel

Trained on PCA-transformed features

Evaluation

Metrics: Accuracy, Precision, Recall, F1-score

Confusion Matrix

📊 Results

Validation Accuracy: ~62.5%

Test Accuracy: ~50%

Classification Report (Test)
              precision    recall  f1-score   support
Cat              0.50      0.66      0.57      2500
Dog              0.50      0.34      0.40      2500

Confusion Matrix (Test)
[[1655  845]
 [1655  845]]
