# **TrueMood - Emotion Recognition ( Model Training )** 
**TrueMood** is a project focused on recognizing human emotions using machine learning. This repository contains the model training code and related resources to analyze and predict emotions based on input data.

<br/>

## Project Overview
- **Objective:** Build a CNN-based model to classify 7 emotions (Angry, Disgust, Fear, Happy, Sad, Surprise, Neutral) from facial expressions.
- **Dataset:** FER-2013, with 35,887 grayscale images.
- **Model Performance:** Achieves 86.29% validation accuracy and 0.38 validation loss after 70 epochs.
- **Technologies:** Python, TensorFlow, Keras, OpenCV (for preprocessing).

<br/>

## Model Details
- **Architecture:** Custom CNN with 6 convolutional layers, max pooling, dropout (25%), and dense layers with softmax output.
- **Input:** 48x48 grayscale images.
- **Training:** Adam optimizer, categorical crossentropy loss, data augmentation (rotation, flipping).
- **Output Format:** Converted to TensorFlow Lite for mobile integration.

<br/>

## Android Integration
The trained model is integrated into a real-time Android app.
- ✅ **Check it out here :** [TrueMood Android App](https://github.com/achelmasoudi/TrueMood_App)

<br/>

## Documentation
For a detailed explanation of the project, including methodology, model architecture, and results, see the attached PDF: [TrueMood Model Training Report](https://github.com/user-attachments/files/19366827/TrueMood_DuyguAnalizi.pdf)
