# Real-Time Emotion-Driven Music Generation System
 
 
This repository contains the code and resources in completion of works towards MSc for Data Science and AI aimed at developing a real-time system that dynamically generates and manipulates musical elements based on facial expression analysis. The system utilizes advanced computer vision techniques, including Convolutional Neural Networks (CNNs), YOLOv5, and Random Forest models to classify four specific emotional states: sadness, happiness, anger, and neutrality. It also generates corresponding music based on these emotional states to create personalized, emotion-driven musical experiences. The goal is to explore the impact of AI and data science on emotional experience through music, with potential applications in therapy, gaming, and immersive experiences.


The system employs several machine learning techniques for emotion recognition and music generation:

- Facial Emotion Recognition (FER): Utilizes a Convolutional Neural Network (CNN) model trained on facial images to detect emotions. Facial landmarks are extracted using Haar Cascades and Dlib’s shape predictor.
- Emotion Classification: A Random Forest model classifies emotions based on distances between key facial features, providing robust emotion recognition.
- Music Generation: The system generates music that corresponds to the detected emotional state, creating a seamless integration between visual and auditory stimuli. Two options are available: 1. manipulate the song choice based on pre-labbelled music or 2. choose a pre-labelled song to manipulate musical elements

Git clone:    git clone https://github.com/n1cffz/Final-thesis-folder-24.git + cd Final-thesis-folder-24

pip install -r requirements.txt

Usage:
Real-Time Emotion Detection: Use a webcam to capture facial expressions and generate music in real-time.
Pre-Recorded Analysis: Analyze pre-recorded videos to explore how different emotions affect music generation.

Future Work:
Expand Emotion Categories: Incorporate additional emotional states for a more nuanced music generation.
Improve Music Generation: Explore advanced music generation techniques to enhance the quality and variety of the output.


