# Real-Time Face Emotion Detection

## Overview
This project is a real-time face emotion detection application built using OpenCV, a custom-trained Convolutional Neural Network (CNN) model, and Streamlit. The application detects human emotions from live webcam feeds and classifies them into five categories: **Angry, Happy, Neutral, Sad, and Surprise**.

## Features
- Real-time face detection using OpenCV's Haarcascade classifier.
- Emotion classification using a pre-trained deep learning model.
- Interactive web-based interface powered by Streamlit.
- Live webcam streaming for emotion recognition.

## Technologies Used
- **Python**
- **OpenCV** (for face detection)
- **TensorFlow/Keras** (for deep learning model)
- **Streamlit** (for web application)
- **Streamlit-WebRTC** (for real-time webcam streaming)
- **NumPy** (for numerical computations)

## Installation
### Prerequisites
Ensure you have Python installed (preferably 3.7 or later). Install dependencies using:
```bash
pip install numpy opencv-python streamlit tensorflow keras streamlit-webrtc
```

### Clone Repository
```bash
git clone https://github.com/your-repository-url.git
cd your-repository-folder
```

## Usage
### Run the Application
```bash
streamlit run app.py
```

### Application Functionalities
1. **Home Page**
   - Overview of the application and its functionalities.
2. **Webcam Face Detection**
   - Click on "Start" to launch the webcam and detect facial emotions in real time.
3. **About**
   - Provides additional details about the project.

## File Structure
```
|-- app.py                # Main application script
|-- emotion_model1.json   # Pre-trained model architecture
|-- emotion_model1.h5     # Pre-trained model weights
|-- haarcascade_frontalface_default.xml  # Face detection model
|-- README.md             # Project documentation
```

## Model Details
The CNN model is trained on a dataset of facial expressions and classifies emotions into the following categories:
- Angry
- Happy
- Neutral
- Sad
- Surprise

## Troubleshooting
- If the face is not detected, ensure proper lighting and position your face closer to the camera.
- Ensure that the required model files (`emotion_model1.json` and `emotion_model1.h5`) are present in the project directory.



## License
This project is licensed under the MIT License - see the LICENSE file for details.
