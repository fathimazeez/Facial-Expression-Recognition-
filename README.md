click here for the project code :https://drive.google.com/drive/folders/1Sxd_h6k1l7MN9AnlH8UKsHCss7QjYDCF?usp=sharing
# Real-Time Facial Expression Recognition using CNN & Computer Vision

## Overview

Real-Time Facial Expression Recognition is a Deep Learning and Computer Vision project that detects human faces from images or live webcam feeds and classifies facial expressions in real time.

The system uses a Convolutional Neural Network (CNN) trained on facial expression datasets to recognize emotions and predict one of the following categories:

* Angry
* Disgust
* Fear
* Happy
* Neutral
* Sad
* Surprise

The project combines OpenCV for face detection, TensorFlow/Keras for deep learning model development, and Python for real-time emotion recognition. It demonstrates how Artificial Intelligence can interpret human emotions from facial expressions and enable intelligent human-computer interaction.

---

## Features

### Real-Time Emotion Detection

* Detects faces from webcam feeds.
* Performs real-time emotion classification.

### Image-Based Prediction

* Analyze facial expressions from uploaded images.
* Supports common image formats.

### Face Detection

* Detects faces using OpenCV Haar Cascades.
* Automatically crops and processes facial regions.

### Deep Learning Classification

* CNN model trained on facial expression datasets.
* High-speed inference for real-time applications.

### User-Friendly Interface

* Displays detected face with emotion label.
* Shows prediction confidence score.

### Deployment Ready

* Can be deployed on local machines, cloud servers, or web applications.

---

## Technology Stack

### Programming Language

* Python

### Deep Learning

* TensorFlow
* Keras

### Computer Vision

* OpenCV

### Data Processing

* NumPy
* Pandas

### Visualization

* Matplotlib
* Seaborn

### Development Environment

* Jupyter Notebook
* VS Code

---

## Project Workflow

```text
Webcam / Image Input
          │
          ▼
     Face Detection
       (OpenCV)
          │
          ▼
 Image Preprocessing
          │
          ▼
 CNN Model Prediction
    (TensorFlow)
          │
          ▼
 Emotion Classification
          │
          ▼
 Display Emotion Label
```

---

## Dataset

The model is trained using a facial expression dataset containing thousands of grayscale facial images labeled with emotion categories.

### Emotion Classes

```text
Angry
Disgust
Fear
Happy
Neutral
Sad
Surprise
```

### Data Preprocessing

* Face extraction
* Grayscale conversion
* Image resizing
* Normalization
* Data augmentation
* Train-Test split

---

## CNN Model Architecture

The Convolutional Neural Network consists of:

* Convolution Layers
* ReLU Activation
* Batch Normalization
* Max Pooling Layers
* Dropout Layers
* Fully Connected Dense Layers
* Softmax Output Layer

### Training Configuration

```python
Optimizer = Adam
Loss Function = Categorical Crossentropy
Batch Size = 32
Epochs = 30-50
Metrics = Accuracy
```

---

## Project Structure

```text
Facial-Expression-Recognition/
│
├── dataset/
│   ├── train/
│   └── test/
│
├── model/
│   ├── emotion_model.h5
│
├── notebooks/
│   ├── Facial_Expression_Training.ipynb
│
├── images/
│   ├── sample_outputs/
│
├── haarcascade_frontalface_default.xml
├── realtime_emotion_detection.py
├── requirements.txt
├── README.md
└── .gitignore
```

---

## Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/facial-expression-recognition.git

cd facial-expression-recognition
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Environment

Windows:

```bash
venv\Scripts\activate
```

Linux/Mac:

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Run Real-Time Detection

```bash
python realtime_emotion_detection.py
```

The webcam will open automatically and display the detected facial expression in real time.

---

## Sample Output

| Face Detected | Predicted Emotion |
| ------------- | ----------------- |
| 😀            | Happy             |
| 😢            | Sad               |
| 😡            | Angry             |
| 😨            | Fear              |
| 😲            | Surprise          |
| 😐            | Neutral           |

---

## Applications

### Human-Computer Interaction

* Emotion-aware systems
* Smart assistants

### Healthcare

* Mental health monitoring
* Patient emotion tracking

### Education

* Student engagement analysis
* E-learning analytics

### Security & Surveillance

* Behavioral monitoring
* Public safety systems

### Marketing & Customer Experience

* Customer sentiment analysis
* Product feedback evaluation

---

## Future Enhancements

* Multi-face emotion recognition
* Emotion trend analytics
* Video stream emotion tracking
* Mobile application integration
* Cloud deployment
* Emotion-based recommendation systems

---

## Results

The trained CNN model successfully detects and classifies facial expressions from webcam streams and images, enabling real-time emotion recognition with high accuracy.

---

## Screenshots

### Real-Time Emotion Detection

![Emotion Detection](screenshots/emotion_detection.png)

### Webcam Prediction

![Webcam Output](screenshots/webcam_output.png)

---

## Author

**Fathima Azeez**

Data Science Trainer | Python Developer | Computer Vision & Deep Learning Enthusiast

---

## License

This project is licensed under the MIT License.

Feel free to use, modify, and contribute to this project.
