🌟 Face Emotion Detection using Deep Learning & Streamlit

Real-time Facial Emotion Recognition System built with TensorFlow, OpenCV, and Streamlit, capable of detecting human emotions from webcam input or uploaded images.
This project identifies emotions like Happy, Sad, Angry, Fear, Surprise, Neutral, Disgust using a trained CNN model.

🚀 Live App (Streamlit Deployment)

आप हमारी live deployed application यहाँ चला सकते हैं:

👉 🔗 https://face-emotion-detection-iameglezm3zc6mrlzu4xyo.streamlit.app/

Webcam open करके “Capture Photo” दबाएँ → App आपका emotion detect करके दिखाएगा।

📸 Features

✔ Real-time Webcam Emotion Detection
✔ Capture Photo directly from camera
✔ Automatic Face Detection
✔ Emotion Prediction using Deep Learning
✔ Bounding box + Label Visualization
✔ Clean & user-friendly Streamlit UI
✔ Supports JPG, JPEG, PNG image uploads

🧠 Emotion Classes

Model निम्न 7 भावनाओं को detect करता है:

😡 Angry

🤢 Disgust

😨 Fear

😀 Happy

😐 Neutral

😢 Sad

😮 Surprise

🗂️ Project Structure
Face-Emotion-detection/
│── app.py                           # Streamlit Web App
│── realtime.py                      # Real-time Webcam Script (OpenCV)
│── train.py                         # Training Script
│── emotion_model.h5                 # Trained CNN Model
│── haarcascade_frontalface_default.xml  # Face Detection Model
│── data/                            # Dataset for training
│── requirements.txt                 # Dependencies
└── README.md

🛠️ Technologies Used

TensorFlow / Keras

OpenCV

Streamlit

NumPy

Pillow

pillow
numpy
