# dverse

README: AI-Based Healthcare Applications

Overview

This repository contains three AI-driven healthcare applications:

Parkinson’s Disease Detection - Identifies early signs of Parkinson’s based on speech patterns.

Hand Landmark Detection - Uses computer vision to detect hand landmarks such as fingertips and joints.

Heart Disease FAQ Chatbot - Provides answers to common heart disease-related questions using NLP.

1. Parkinson’s Disease Detection

Description:
This model analyzes speech data to detect early signs of Parkinson’s disease. It uses machine learning algorithms trained on a dataset containing speech features of Parkinson’s patients.

Dataset:

The dataset includes speech recordings with extracted acoustic features.

Common features: jitter, shimmer, harmonic-to-noise ratio (HNR), and pitch variations.

Implementation Steps:

Load the dataset and preprocess audio features.

Train a classification model (e.g., SVM, Random Forest, or Neural Networks).

Evaluate performance using accuracy and F1-score.

Deploy the model for real-time analysis.

Usage:
Run the script to input speech samples and get a prediction on potential Parkinson’s indicators.

2. Hand Landmark Detection

Description:
This system detects and tracks hand landmarks (fingertips, joints) using computer vision and deep learning models.

Implementation Steps:

Utilize MediaPipe Hands API for real-time hand detection.

Extract key landmarks such as fingertips and wrist positions.

Overlay detected points on live video feed.

Integrate with gesture recognition for interactive applications.

Usage:

Run the program with a webcam to see real-time hand tracking.

Integrate with applications requiring gesture-based control.

3. Heart Disease FAQ Chatbot

Description:
A chatbot that provides answers to common heart disease questions using NLP and text similarity techniques.

Dataset:

Contains FAQs about heart disease, symptoms, causes, treatments, and prevention.

Uses TF-IDF and cosine similarity to find the most relevant answer.

Implementation Steps:

Preprocess a dataset of frequently asked questions.

Convert questions into TF-IDF vectors for similarity matching.

Use cosine similarity to find the closest match to a user’s query.

Provide responses in a chatbot interface.

Usage:

Run the chatbot script.

Enter queries about heart disease to receive responses.

Type 'exit' to quit the chatbot.

