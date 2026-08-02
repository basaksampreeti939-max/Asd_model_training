Introduction 

Designed and developed an AI-based ASD early screening system that analyzes facial expressions to detect emotional and behavioral patterns associated with Autism Spectrum Disorder. Built using Python, TensorFlow, OpenCV, Streamlit, and EfficientNet, the system provides a quick, non-invasive preliminary screening tool to support early identification and timely intervention.

🧠 Project Overview

ASD Early Screening System is an AI-powered application designed to support the early screening of Autism Spectrum Disorder (ASD) through automated analysis of facial expressions. The system leverages computer vision and deep learning techniques to detect faces, analyze facial expressions, and identify emotional patterns that may differ from typical developmental behavior.Using facial images or live webcam input, the application detects a face, preprocesses the image, and applies a trained facial emotion recognition model to classify emotions such as happy, sad, angry, fear, surprise, disgust, and neutral. By analyzing the distribution and consistency of these emotional responses over time, the system generates an ASD screening score that indicates whether the observed facial expression patterns resemble characteristics commonly associated with ASD.

✨ Features

👤 Face Detection:
Automatically detects and extracts the face from an uploaded image or live webcam feed using computer vision techniques.

😀 Facial Emotion Recognition:
Classifies facial expressions into seven universal emotions:

Happy
Sad
Angry
Fear
Surprise
Disgust
Neutral
🤖 AI-Based ASD Screening:
Analyzes facial expression patterns and estimates the likelihood of ASD-related emotional characteristics to support early screening.

📷 Image Upload Support:
Allows users to upload facial images for analysis and prediction.

🎥 Real-Time Webcam Analysis:
Performs live facial expression detection and emotion recognition using a webcam.

📊 Confidence Score Display:
Displays the confidence level for each predicted emotion and screening result.

📈 Emotion Distribution Visualization:
Shows probability graphs and charts illustrating the detected emotional patterns.

📋 Screening Report:
Generates a summary report containing:
Detected emotion
Confidence score
ASD screening likelihood
Screening recommendation

🧠 System Workflow
                User Input
                    │
                    ▼
        Upload Image / Live Webcam
                    │
                    ▼
      Face Detection (MediaPipe/OpenCV)
                    │
                    ▼
         Face Cropping & Alignment
                    │
                    ▼
          Image Preprocessing
    • Resize (48×48)
    • Grayscale Conversion
    • Normalization
                    │
                    ▼
        Emotion Recognition Model
    (CNN / MobileNetV2 / ResNet50)
                    │
                    ▼
      Emotion Classification
   ┌──────────────────────────────┐
   │ Angry                        │
   │ Disgust                      │
   │ Fear                         │
   │ Happy                        │
   │ Sad                          │
   │ Surprise                     │
   │ Neutral                      │
   └──────────────────────────────┘
                    │
                    ▼
      Display Prediction Result
    • Predicted Emotion
    • Confidence Score
    • Probability Graph
                    │
                    ▼
     Emotion History & Analytics

     🔍 Prediction Pipeline
     Input Image
      │
      ▼
Face Detection
(OpenCV / MediaPipe)
      │
      ▼
Face Extraction
      │
      ▼
Image Preprocessing
      │
      ▼
CNN Model Prediction
      │
      ▼
Softmax Layer
      │
      ▼
Emotion Label
      │
      ▼
Confidence Score
      │
      ▼
Visualization on Streamlit Dashboard

Technologies Used
Python 3.10+
TensorFlow
Keras
NumPy
Pandas
Matplotlib
Seaborn
Plotly
Git
GitHub
Dataset
FER2013 (Kaggle)
