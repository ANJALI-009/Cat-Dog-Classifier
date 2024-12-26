# 🐱 vs 🐶 Image Classification App

A Streamlit web application that classifies uploaded images as either a cat or a dog using a pre-trained ResNet18 model.

## 🚀 Features

- Simple and intuitive user interface
- Real-time image classification
- Displays prediction confidence scores
- Supports multiple image formats (JPG, JPEG, PNG)
- Powered by PyTorch and ResNet18 architecture

## 📋 Prerequisites

Before running this application, make sure you have the following installed:
- Python 3.7+
- Streamlit
- PyTorch
- Torchvision
- Pillow (PIL)
- NumPy


## 🔧 Installation

1. Clone this repository
2. Install the required packages
3.execute the following command in your terminal 
streamlit run app.py


The app will open in your default web browser at `http://localhost:8501`.

## 📝 Usage

1. Launch the application
2. Click on "Choose an image..." to upload your image
3. Wait for the model to process the image
4. View the prediction result and confidence score

## 🛠️ Technical Details

- The application uses a pre-trained ResNet18 model from PyTorch's model zoo
- Images are preprocessed to 224x224 pixels and normalized
- The model uses ImageNet class indices 208 (dog) and 283 (cat) for classification
- Predictions are normalized between cat and dog probabilities


## ⚠️ Limitations

- The model is trained on specific cat and dog images and may not perform well on unusual angles or obscured images
- Classification is binary (cat or dog) and may not properly handle other types of images

