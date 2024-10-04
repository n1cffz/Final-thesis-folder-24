# Real-Time Emotion-Driven Music Generation System
 
 
This repository contains the code and resources in completion of works towards MSc for Data Science and AI aimed at developing a real-time system that dynamically generates and manipulates musical elements based on facial expression analysis. The system utilizes advanced computer vision techniques, including Convolutional Neural Networks (CNNs), YOLOv5, and Random Forest models to classify four specific emotional states: sadness, happiness, anger, and neutrality. It also generates corresponding music based on these emotional states to create personalized, emotion-driven musical experiences. The goal is to explore the impact of AI and data science on emotional experience through music, with potential applications in therapy, gaming, and immersive experiences.

To clone the repositiory: git clone https://github.com/n1cffz/Final-thesis-folder-24.git
cd emotion-driven-music-generation

The system employs several machine learning techniques for emotion recognition and music generation:

Facial Emotion Recognition (FER): A CNN model trained on facial images detects emotions. Haar Cascades and Dlib’s shape predictor extract facial landmarks.
Random Forest Model: Uses facial landmark data to classify emotions based on distances between key facial features.

