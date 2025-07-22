# Face_Tracking_Model

This project demonstrates real-time face detection using OpenCV and a pre-trained Haar Cascade classifier. It serves as the foundation for a broader facial expression recognition system using deep learning.

---

## Demo Video

👉 [Watch the Demo](https://youtu.be/TCDzxH6mCwU)

## Project Overview

This project consists of two main components:

1. **Model Training (ResNet50):**
   - Trained on a merged dataset of FER2013 and custom-labeled facial images.
   - Emotion classes used: Angry, Happy, Sad, Surprise, Neutral.
   - Preprocessing includes grayscale conversion, resizing, label encoding, and normalization.
   - Implemented in PyTorch with transfer learning from a pretrained ResNet50.

2. **Real-Time Face Tracking:**
   - Implemented with OpenCV in a Jupyter Notebook.
   - Uses Haar Cascade classifier to detect faces from webcam feed.
   - Displays bounding boxes over detected faces.

---

## 🧰 Technologies Used

- Python 3.12
- PyTorch
- torchvision
- OpenCV
- Jupyter Notebook
