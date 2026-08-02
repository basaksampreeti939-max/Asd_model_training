# Introduction

Designed and developed an AI-based ASD early screening system that analyzes facial expressions to detect emotional and behavioral patterns associated with Autism Spectrum Disorder. Built using Python, TensorFlow, OpenCV, Streamlit, and EfficientNet, the system provides a quick, non-invasive preliminary screening tool to support early identification and timely intervention.
## 🧠 Project Overview

ASD Early Screening System is an AI-powered application designed to support the early screening of Autism Spectrum Disorder (ASD) through automated analysis of facial expressions. The system leverages computer vision and deep learning techniques to detect faces, analyze facial expressions, and identify emotional patterns that may differ from typical developmental behavior.Using facial images or live webcam input, the application detects a face, preprocesses the image, and applies a trained facial emotion recognition model to classify emotions such as happy, sad, angry, fear, surprise, disgust, and neutral. By analyzing the distribution and consistency of these emotional responses over time, the system generates an ASD screening score that indicates whether the observed facial expression patterns resemble characteristics commonly associated with ASD.
## ✨ Features

Face Detection:

Automatically detects and extracts the face from an uploaded image or live webcam feed using computer vision techniques.

Facial Emotion Recognition

Classifies facial expressions into seven universal emotions:

Happy
Sad
Angry
Fear
Surprise
Disgust
Neutral

AI-Based ASD Screening

Analyzes facial expression patterns and estimates the likelihood of ASD-related emotional characteristics to support early screening.

 Image Upload Support

Allows users to upload facial images for analysis and prediction.

Real-Time Webcam Analysis

Performs live facial expression detection and emotion recognition using a webcam.

## Class Diagram 

The class diagram outlines the core classes in the system, their attributes and relationships between them.

<img width="975" height="837" alt="Image" src="https://github.com/user-attachments/assets/41632615-5464-4d77-bea5-eec387f7f861" />

## Model Architecture (FER2013 Dataset)

The proposed model is a Convolutional Neural Network (CNN) designed for facial emotion recognition using the FER2013 dataset. The input is a 48 × 48 grayscale facial image, which undergoes preprocessing, including resizing and normalization. The CNN consists of multiple Convolutional layers with ReLU activation to extract facial features, followed by Max Pooling layers to reduce spatial dimensions and Dropout layers to minimize overfitting. The extracted features are then flattened and passed through Fully Connected (Dense) layers for classification. Finally, a Softmax output layer predicts one of the seven facial emotions: Angry, Disgust, Fear, Happy, Sad, Surprise, or Neutral. This architecture enables accurate emotion recognition and serves as the core component for facial expression analysis in the ASD early screening system.

## Future Work
There are various ways in which the current project can be improved to increase the precision, usability, and 
practicality of the system:
* Training and comparing other machine learning algorithms like XGBoost, LightGBM, and Artificial Neural Network 
(ANN).
* Incorporating larger and more diverse datasets with the addition of data from various countries, age groups, 
and healthcare institutes.
* Conducting feature selection and hyperparameter tuning to further increase classification performance.
* Developing a web/mobile application that will allow parents and healthcare practitioners to conduct ASD 
screening quickly.
* Developing a multimodal ASD detector using image-based, speech-based, and facial expression analysis along 
with questionnaire-based features.
* Validating the current model on clinical real-world datasets and conducting prospective studies.
These enhancements would allow the model to become more reliable and accurate.

 ## Result
evelopment and evaluation of the machine learning classifiers for the Autism Spectrum Disorder (ASD) detection 
odel were successful. Missing value imputation, categorical
ariable encoding, and feature scaling processes were conducted during data preprocessing to enhance classifier 
erformance. Exploratory Data Analysis (EDA) enabled finding
ome important connections between the features. Several classifiers were trained and compared in order to find 
ut which one could be used for ASD prediction with the highest
fficiency. It turned out that the chosen model performed very well on the testing data set by providing high 
lassification accuracy as well as good values of precision,
ecall, and F1-score. Confusion matrix and ROC curve analysis proved that the classifier was able to 
ifferentiate ASD-positive and ASD-negative samples efficiently.

## Conclusion
It has been illustrated from this project that machine learning algorithms can be used efficiently for detecting 
Autism Spectrum Disorder at an early stage based on behavioral,
demographic, and clinical variables. As a result of preparing the dataset and developing different classifiers, 
the final classifier showed good prediction capability. The
significance of appropriate data preparation, feature selection, and model development for constructing an 
efficient diagnosis system has been shown.
This developed model can act as a supporting decision-making mechanism for medical professionals for detecting 
the children who are at risk of having autism at an early stage.
Although this model cannot be considered as a replacement for clinical diagnosis, it can help in identifying the 
children who need further medical assistance.

## Disclaimer

This project is developed solely for educational, research, and early screening purposes. It is not intended to diagnose Autism Spectrum Disorder (ASD) or replace professional medical evaluation. The results generated by the system should be considered preliminary and must be interpreted only with guidance from qualified healthcare professionals.

## License

This project is released under the MIT License.

## Author 

Developed by Sampreeti Basak and Srija Ghosh
