# Object Detection System

A Deep Learning-based Custom Object Detection System developed using YOLO and PyTorch. This project uses transfer learning to train a custom object detection model capable of identifying and localizing specific objects within images. The trained model is integrated with a Flask web application, allowing users to upload images and receive real-time object detection results.

---
<img width="1317" height="715" alt="image" src="https://github.com/user-attachments/assets/bc8abe71-86b6-4a4e-89ff-c737207d92ec" />


## Project Overview

Object detection is a computer vision task that involves identifying and locating objects within an image. Unlike image classification, object detection not only predicts the object class but also determines its exact location using bounding boxes.

In this project, a pre-trained YOLO (You Only Look Once) model is fine-tuned using transfer learning on a custom dataset. The model learns to detect and classify custom objects efficiently while maintaining high accuracy and fast inference speed.

The trained model is deployed through a Flask-based web application, providing an easy-to-use interface for performing object detection on uploaded images.

---

## Objectives

The primary objectives of this project are:

- Develop a custom object detection system using Deep Learning.
- Apply transfer learning to improve model performance.
- Detect and localize objects accurately.
- Create a user-friendly web interface for predictions.
- Demonstrate practical applications of Computer Vision.

---

## Features

### Deep Learning Features

- Custom object detection
- Object localization using bounding boxes
- Transfer learning implementation
- Fine-tuning of pre-trained weights
- Data preprocessing and augmentation
- Model evaluation and testing

### Web Application Features

- Image upload functionality
- Real-time object detection
- Detection visualization
- Bounding box generation
- Prediction confidence scores
- User-friendly Flask interface

---

## Model Architecture

### Model Used

**YOLO (You Only Look Once)**

YOLO is a state-of-the-art object detection algorithm designed for real-time object detection applications.

### Techniques Applied

- Transfer Learning
- Fine-Tuning
- Data Augmentation
- Object Localization
- Bounding Box Regression
- Confidence Score Prediction

---

## Technologies Used

### Programming Language
- Python

### Deep Learning Framework
- PyTorch

### Computer Vision
- YOLO
- OpenCV

### Data Processing
- NumPy
- Pandas

### Visualization
- Matplotlib

### Web Development
- Flask
- HTML
- CSS
- JavaScript

### Development Tools
- Jupyter Notebook
- VS Code
- Git
- GitHub

---

## Project Structure

```text
Custom-Object-Detection/
│
├── Code.ipynb
├── app.py
├── best_model.pt
├── dataset/
│
├── static/
│
├── templates/
│
├── README.md
└── requirements.txt
```

---

## System Workflow

```text
Input Image
      ↓
Image Preprocessing
      ↓
YOLO Object Detection Model
      ↓
Feature Extraction
      ↓
Object Detection
      ↓
Bounding Box Generation
      ↓
Confidence Score Calculation
      ↓
Prediction Result
```

---

## Training Process

The model training pipeline includes:

### Step 1
Collect and prepare the custom dataset.

### Step 2
Annotate images with object labels and bounding boxes.

### Step 3
Apply data preprocessing and augmentation.

### Step 4
Load pre-trained YOLO weights.

### Step 5
Perform transfer learning and fine-tuning.

### Step 6
Train and validate the model.

### Step 7
Save the best-performing model.

---

## Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/Custom-Object-Detection.git
```

### Move into Project Directory

```bash
cd Custom-Object-Detection
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Flask Application

```bash
python app.py
```

Open your browser:

```text
http://127.0.0.1:5000
```

---

## Application Workflow

1. Open the web application.
2. Upload an image.
3. Click the detection button.
4. The model processes the image.
5. Detected objects are displayed with bounding boxes and confidence scores.

---

## Applications

- Smart Surveillance
- Industrial Automation
- Healthcare Imaging
- Traffic Monitoring
- Agricultural Monitoring
- Retail Analytics
- Security Systems

---

## Future Improvements

- Real-time webcam detection
- Video object detection
- Cloud deployment
- Mobile application support
- Multi-object tracking
- Performance optimization

---

## Author

### Mohsin Ali

Machine Learning Enthusiast | Computer Vision Learner | Python Developer

---

## License

This project is developed for educational and learning purposes.
