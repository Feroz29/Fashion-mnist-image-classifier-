# 👕 Fashion MNIST Image Classifier | Deep Learning + Streamlit

A deep learning web application that classifies fashion items (like T-shirts, sneakers, and coats) from grayscale images using a Convolutional Neural Network (CNN). Built with TensorFlow and deployed using Streamlit, the app provides real-time predictions from user-uploaded images.

---

##  Introduction

The goal of this project is to combine deep learning with user-friendly deployment. Using the **Fashion MNIST dataset**, I trained a CNN to identify 10 types of clothing from 28x28 grayscale images. The model is integrated into a **Streamlit web app**, where users can upload an image and get a prediction instantly.

This project helped me learn and apply key deep learning concepts like image preprocessing, model evaluation, and real-world deployment using Streamlit.

---

##  Objectives

- Build a CNN model to classify images from the Fashion MNIST dataset
- Save and reuse the trained model using `.h5` format
- Create an interactive UI using Streamlit for real-time predictions
- Deploy the model for easy public use and demonstration

---

##  Key Insights

- **Model Accuracy:** Achieved ~90% accuracy on the test set using a simple CNN architecture
- **Consistent Prediction:** The model reliably predicts well on images with clear shapes and outlines
- **User-Friendly Interface:** Streamlit allows fast, clean deployment without heavy backend setup
- **Real-World Use Case:** Similar techniques are used in e-commerce for product tagging and image search

---

##  Classes Predicted

The model predicts the following fashion categories:
1. T-shirt/top  
2. Trouser  
3. Pullover  
4. Dress  
5. Coat  
6. Sandal  
7. Shirt  
8. Sneaker  
9. Bag  
10. Ankle boot

---

##  Technologies Used

- `TensorFlow/Keras` – for building and training the CNN
- `Streamlit` – for building the web interface
- `NumPy`, `Pillow (PIL)` – for image processing and array handling
- `Google Colab` – for model development and training

---
## How It Works

1. **Upload an Image:** User uploads a PNG/JPG image of clothing (preferably grayscale).
2. **Image Preprocessing:** The image is resized to 28x28 pixels, normalized, and reshaped.
3. **Model Prediction:** The pre-trained CNN model processes the image and outputs class probabilities.
4. **Prediction Display:** The app shows the most likely clothing item along with a confidence score.
   
---
## Author
Feroz Deen K
Deep Learning & Data Science Enthusiast
ferozdeen12@gmail.com
