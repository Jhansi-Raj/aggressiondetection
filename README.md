# Aggressiondetection
My internship assignment involves creating a research documentation,prototype documentation and the Python script that takes audio files as input for Aggression detection in speech or audio.
# Introduction
This Aggression Detection Prototype is designed to detect aggression in audio data using machine learning. It combines audio-based feature extraction with emotion classification to identify aggression in spoken content. The prototype utilizes a Multi-Layer Perceptron (MLP) classifier and is designed to provide users with a simple tool for emotion detection.

# Features
Audio-based feature extraction including MFCC, chroma, and mel features.
Training an MLP classifier for emotion classification.
User-friendly interface for audio input and emotion prediction.
Accuracy and F1 score reporting.
Model serialization for future use.

# Prerequisites
Before using the prototype, make sure you have the following prerequisites:

Python 3.7 or higher installed.
Required Python libraries: librosa, soundfile, numpy, scikit-learn, pandas.

# Input
Audio Files: Place your audio files in the project directory. Supported formats include MP3, WAV, and other common audio formats containing spoken content.
Analysis
Feature Extraction: The prototype extracts audio features (MFCC, chroma, mel) from the provided audio files.

Model Training: The MLP classifier is trained on the extracted features to classify emotions, with a focus on detecting aggression.

# Output
Accuracy: The prototype reports an accuracy score to indicate how well the model performs in aggression detection.

F1 Scores: F1 scores for individual emotions (e.g., 'calm,' 'disgust,' 'happy,' 'fearful') are provided.

Emotion Predictions: Users can predict emotions for their audio data using the trained model. A sample prediction ('disgust') is demonstrated in the code.

# Model Serialization: The trained model is saved to a file for future use.

# Prototype Documentation
For detailed documentation of the prototype, including its approach, features, preprocessing steps, and user manual, please refer to the Prototype Documentation file.

# License
This project is licensed under the GNU License - see the LICENSE file for details.
