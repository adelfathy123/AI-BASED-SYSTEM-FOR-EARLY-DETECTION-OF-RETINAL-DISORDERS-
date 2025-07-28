# AI-BASED-SYSTEM-FOR-EARLY-DETECTION-OF-RETINAL-DISORDERS-
🔍 AI-Based System for Early Detection of Retinal Disorders An intelligent deep learning system that classifies 7 retinal diseases from OCT images using CNN models like VGG16, SqueezeNet, and InceptionV3. Designed to assist ophthalmologists by providing fast, accurate, and automated diagnosis — even for rare retinal conditions.
# AI-Based System for Early Detection of Retinal Disorders

This project leverages deep learning to detect and classify retinal disorders from OCT (Optical Coherence Tomography) images. It focuses on 7 retinal diseases, using CNN models like VGG16, SqueezeNet, and InceptionV3.

## 📌 Features
- Multi-class classification of 7 retinal diseases.
- Data augmentation and class balancing.
- Model comparison with accuracy and F1-score.
- Gradio-based interactive interface.
- Hybrid model using feature-level fusion + traditional ML classifiers.

## 📊 Models Used
- VGG16 (with/without augmentation)
- SqueezeNet (lightweight for edge deployment)
- InceptionV3 (high accuracy with fine-tuning)
- Hybrid Model (CNN + SVM, RF, etc.)

## 📁 Dataset
- 2,064 OCT images from 821 patients.
- 7 classes: AMD, DME, ERM, NO, RVO, VID, RAO.
- Final dataset after augmentation: 18,576 images.

> Due to size, full dataset is not hosted in this repo. You can download it from [https://drive.google.com/drive/folders/1Md3_0QZZtQ3XMWqThqbzUPoVlo7QMyOE?usp=drive_link].

## 📈 Performance (Best Model - InceptionV3)
- Accuracy: 97.73%
- F1 Score: 97.73%
- Sensitivity: 97.73%
- Specificity: 97.75%

## 💻 How to Run
```bash
pip install -r requirements.txt
python gradio_interface/app.py
