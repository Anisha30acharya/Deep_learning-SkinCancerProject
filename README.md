🩺 Skin Cancer Image Classification Web App
-----------------------------------------------------
📌 Project Overview:
-------------------------
This project is a web-based skin cancer classification tool.
It uses a trained deep learning model (CNN) to predict the type of skin lesion from uploaded images.

✅ Built using:
---------------------
Python

Flask (Web Framework)

TensorFlow / Keras (For Model)

HTML / CSS (For Web Interface)

🔧 Project Folder Structure:
--------------------------------
skin cancer project/
├── .idea/                           # PyCharm project files (optional)
├── flask2/
│   ├── app.py                       # Main Flask application
│   ├── HAM10000_metadata.csv        # Dataset metadata (reference info)
│   ├── skin_cancer_model.h5         # Trained CNN model file
│   ├── class_names.pkl              # Pickle file containing class label names
│   └── static/
│       └── uploads/                 # Sample test images for testing the app

Flask backend code to handle:
✅ Image upload
✅ Model loading
✅ Prediction generation
✅ Displaying results on the web page

skin_cancer_model.h5 (Trained Model):

Pre-trained Convolutional Neural Network (CNN)

Accepts skin lesion images and outputs predicted cancer type

HAM10000_metadata.csv (Dataset Info):

Contains the original metadata about the images (age, sex, lesion type, etc.)

Used for reference and analysis

class_names.pkl (Class Labels):

Python Pickle file

Maps predicted class indices to human-readable class names (like melanoma, nv, bcc, etc.)

static/uploads/

Contains sample skin lesion images for testing the app

User can upload new images via the web interface

🎯 Project Features:
----------------------------
✅ Upload a skin lesion image via web browser
✅ Get real-time classification result (e.g., Melanoma, Nevus, BCC, etc.)
✅ Displays predicted class with confidence scores (optional)

🧱 Technologies Used:
----------------------
Python

Flask (Web framework)

TensorFlow/Keras (Model building & training)

HTML / CSS (For Frontend)

Pickle (For saving class labels)

✅ Purpose of the Project:
-------------------------------
Early detection support for skin cancer using AI

Demonstrate end-to-end ML deployment with Flask

Educational tool for medical image classification

