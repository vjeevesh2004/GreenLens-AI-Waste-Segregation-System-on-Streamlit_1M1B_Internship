# GreenLens-AI-Waste-Segregation-System-on-Streamlit_1M1B_Internship
An automated waste classification system using deep learning that classifies waste images into predefined categories by fine-tuning a DenseNet169 model pretrained on ImageNet. This project aims to reduce human error in waste sorting and improve recycling efficiency.

# Project Overview

1. Dataset: 15,000 images of various types of waste
2. Goal: Build a high-accuracy automated waste classification system
3. Planned Epochs: 50
4. Target Accuracy: 95%+

# Planned Steps

1. Data Import – Load dataset from Kaggle or other sources.
2. Data Exploration – Analyze category distribution and image counts.
3. Data Splitting – Create training, validation, and test sets.
4. Exploratory Data Analysis (EDA) – Visualize images and inspect patterns.
5. Image Copying & Organization – Organize images into structured directories.
6. TensorFlow Dataset Preparation – Build tf.data pipelines for efficient training.
7. Image Augmentation – Apply KerasCV augmentations (RandomFlip, RandomCropAndResize, CutMix, MixUp).
8. Model Building – Construct DenseNet169 with a custom classifier head.
9. Training Phase 1 – Train only the classifier head while freezing the backbone.
10. Training Phase 2 – Fine-tune top layers of DenseNet169.
11. Evaluation – Measure accuracy on validation and test sets.
12. Optimization – Use learning rate scheduling, early stopping, and regularization to prevent overfitting.
13. Deployment – Export the trained model for inference in real-world applications.

# Steps Completed

1. Data Import – Dataset imported from Kaggle.
2. Data Exploration – Image counts per category checked.
3. Data Splitting – Training, validation, and test sets created.
4. EDA – Sample images and category distributions visualized.
5. Image Copying & Organization – Images structured into category-wise directories.
6. TensorFlow Dataset Preparation – Efficient tf.data pipelines created for training and validation.
7. Image Augmentation – Applied KerasCV augmentations: RandomFlip, RandomCropAndResize, CutMix, MixUp.
8. Model Building – DenseNet169 with custom classifier head constructed and compiled.

# Technologies Used

Python

TensorFlow & Keras

KerasCV

NumPy, Pandas

Matplotlib, Seaborn
