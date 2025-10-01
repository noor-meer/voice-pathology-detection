# Voice-pathology-detection

⚠️ Disclaimer: This project is for research and educational purposes only.  
It is not a medical diagnostic tool and should not be used to make clinical decisions.  
Always consult healthcare professionals for medical concerns.

## Overview

This project demonstrates voice pathology analysis using **YAMNet**, a pre-trained deep learning model for audio event detection. The model analyzes voice recordings to identify potential vocal disorders and pathologies.

## Voice Pathology Dataset (Kaggle)

https://www.kaggle.com/datasets/pranaykoppula/torgo-audio

## The workflow

1. Dataset preparation (structured in folders per class)  
2. Feature extraction using YAMNet embeddings  
3. Transfer learning and model fine-tuning  
4. Pathology classification and analysis

## Key Features
- **YAMNet-based analysis** for voice pathology detection
- Transfer learning approach for medical audio classification
- Support for both healthy and pathological voice samples
- Comprehensive audio preprocessing pipeline

## Dataset Preparation
- Organize your dataset in separate folders for each class (healthy vs pathological)
- Ensure audio files are in supported formats (WAV, MP3, etc.)
- Maintain balanced classes for optimal training

## Model Architecture
- **Base Model**: YAMNet (pre-trained on AudioSet)
- **Custom Classifier**: Dense layers for pathology classification
- **Output**: Binary classification (healthy vs pathological)

## Usage
- **GOOGLE COLLAB AND JUPYTER NOTEBOOK CAN BE USED FOR TRAINING**
- Update the dataset path to your local directory
- The model will automatically extract YAMNet features and train the classifier

## Requirements
- TensorFlow 2.x
- TensorFlow Hub (for YAMNet)
- Librosa
- NumPy
- Scikit-learn

**SPLIT THE DATASET INTO TRAINING AND TESTING SETS FOR PROPER EVALUATION**
