🩺 Skin Cancer Image Classification Web App
----------------------------------------------
📌 Project Overview
---------------------
This project is a web-based skin cancer classification tool.
It uses a trained deep learning CNN model to predict the type of skin lesion from uploaded images.

Built using:
---------------
Python
Flask (Web Framework)
TensorFlow / Keras (Deep Learning)
HTML / CSS (Frontend)

📌 Key Components
---------------------
1. app.py (Flask Web App)
Handles:

 Image upload

 Model loading

 Prediction generation

 Displaying results on a web page

2. skin_cancer_model.h5 (Trained Model)
 Pre-trained CNN for skin lesion classification

 Takes an image input and outputs predicted skin cancer type

3. class_names.pkl (Class Label Mapping)
Maps class indices (numeric) to readable labels like:

 Melanoma

 Nevus

 BCC (Basal Cell Carcinoma)

 etc.

4. static/uploads/ (Sample Images Folder)
 Contains sample lesion images for testing

 Users can upload their own images through the web app

🎯 Project Features
-------------------------
Upload a skin lesion image via web browser

Get instant classification results (example: Melanoma, BCC, NV)

Display predicted class and optionally confidence scores

🧱 Technologies Used
----------------------
Python

Flask

TensorFlow / Keras

HTML / CSS

Pickle (for storing class labels)

✅ Purpose of the Project
-------------------------------
To demonstrate AI-based skin cancer detection

To learn model deployment with Flask

For educational and research purposes (Not for real-world diagnosis)
