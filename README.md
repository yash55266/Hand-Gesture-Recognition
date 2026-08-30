# Hand Gesture Recognition ✋

A beginner computer vision project that detects hand gestures in real time using a webcam and classifies them using a trained TensorFlow model.

## 📌 About the Project

This project uses a webcam to detect a hand and recognize different hand gestures.

Currently, the model is trained to recognize:

- A
- B
- C

The hand is detected using `cvzone` and MediaPipe, while TensorFlow/Keras is used to classify the processed hand image.

## 🛠️ Technologies Used

- Python 3.10
- OpenCV
- cvzone
- MediaPipe
- TensorFlow
- Keras
- NumPy

## 📂 Project Structure

```text
Hand-Gesture-Recognition/
│
├── Model/
│   ├── keras_model.h5
│   └── labels.txt
│
├── dataCollection.py
├── test.py
── README.md
