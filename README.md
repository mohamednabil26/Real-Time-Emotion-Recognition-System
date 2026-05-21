# Real-time Emotion Recognition — Hybrid CNN & LSTM Architecture with Computer Vision

In human-computer interaction (HCI) and smart applications, understanding human emotions dynamically is a key challenge. Traditional models often struggle to capture facial expressions efficiently in real-time due to varying lighting conditions, facial angles, and the computational cost of continuous video streaming.

To solve this, we developed an intelligent, end-to-end Real-time Emotion Recognition System. The project leverages a high-performance Hybrid Deep Learning model that combines Convolutional Neural Networks (CNN) for spatial feature extraction and Long Short-Term Memory (LSTM) networks to refine the emotion tracking over sequential video frames.

Our system integrates directly with a live webcam feed using OpenCV, automatically detecting faces via Haar Cascade Classifiers, pre-processing the regions of interest (ROI), and predicting one of the 7 core human emotions (Angry, Disgust, Fear, Happy, Neutral, Sad, Surprise) instantly on screen.

What makes this project unique is its optimization for low-latency inference on consumer-grade hardware, making it a highly practical solution for applications in smart education, customer feedback analysis, and healthcare.

## 🛠️ Tech Stack
* **Deep Learning Frameworks:** TensorFlow / Keras
* **Hybrid Neural Network:** Convolutional Neural Networks (CNN) + Long Short-Term Memory (LSTM)
* **Computer Vision:** OpenCV (Haar Cascade Classifiers for live face tracking & ROI extraction)
* **Data Preprocessing & Augmentation:** ImageDataGenerator (Grayscale conversion, rotation, shearing, and rescaling)
* **Data Analysis & Visualization:** Performance monitoring using Pandas, NumPy, and Matplotlib
