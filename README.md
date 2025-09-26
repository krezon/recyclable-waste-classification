Recyclable Waste Classification

This repository contains an image classification project developed as part of the Global AI Hub bootcamp. The goal is to classify recyclable and household waste into the correct categories using deep learning.

📌 Introduction

The dataset used: Recyclable and Household Waste Classification Dataset

30 classes, around ~500 images per class

All images are in .png format

The model is based on EfficientNet-B0.

Applied various data augmentation techniques.

Used transfer learning followed by fine-tuning.

Added advanced methods such as MixUp, label smoothing, and Cosine Annealing LR scheduler.

Technical explanations of the project are included inside the notebook file recyclable-waste-classification.ipynb with detailed markdown cells.

📊 Metrics

Results obtained after training:

Validation Accuracy: ~84%

Test Accuracy: ~83%

A confusion matrix was visualized to analyze class-based performance.

Strengths:

Strong generalization capability thanks to augmentation.

Lightweight and efficient due to the EfficientNet base.

Challenges:

Some visually similar categories are harder to distinguish (e.g., cardboard_boxes vs cardboard_packaging).

🚀 Extras

Grad-CAM visualization was used to understand which image regions the model focuses on.

Performed quick Hyperparameter Optimization (HPO) to improve learning rate and weight decay selection.

✅ Conclusion & Future Work

This work successfully classifies recyclable waste using an EfficientNet-B0-based model with competitive accuracy.

Future improvements:

Experiment with larger EfficientNet models (B3, B4).

Deploy a real-time camera-based demo or a simple Streamlit web app.

Extend the dataset to further improve accuracy.

This project provides a sustainable foundation for AI-powered environmental solutions.

🔗 Links

Kaggle Dataset
