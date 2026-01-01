# Face-Detection-and-recognition-System-Syntecxhub-Task--3-

📌 Project Overview

This project implements a Face Detection and Face Recognition system using OpenCV and Python.
It can detect multiple faces from images or live video streams and recognize known faces by comparing facial features. The system also provides functionality to add new people dynamically by capturing and registering their faces.

This project is suitable for learning computer vision concepts and real-world applications such as attendance systems, security, and surveillance.

🎯 Objectives

- Detect faces from images and live webcam video

- Recognize known faces using face embeddings

- Handle multiple faces in a single frame

- Draw bounding boxes and labels on detected faces

- Add and register new users easily

  🛠️ Technologies Used

Python 3

- OpenCV (cv2)

- face_recognition library

- NumPy

- Haar Cascade / DNN (for face detection)

📂 Project Structure

Face-Detection-Recognition/
│
├── dataset/

│   ├── person1/

│   │   ├── img1.jpg

│   │   └── img2.jpg

│   ├── person2/

│
├── models/

│   └── haarcascade_frontalface_default.xml
│
├── add_face.py

├── face_recognition_app.py

├── encode_faces.py

├── requirements.txt

└── README.md

⚙️ Features

✔ Face detection using OpenCV

✔ Face recognition using facial embeddings

✔ Multiple face handling

✔ Real-time webcam recognition

✔ Bounding boxes with name labels

✔ Easy registration of new users

🧠 Working Principle

Face Detection

Detect faces using Haar Cascade or DNN-based models.

Face Encoding

Extract unique facial features (embeddings).

Face Recognition

Compare detected faces with known embeddings.

Labeling

Display name and bounding box on video frames.

User Registration

Capture images and add new faces to the dataset.

📸 Output

Detects faces in real time

Shows bounding boxes

Displays recognized person’s name

Marks unknown faces as Unknown

🔮 Future Enhancements

Mask detection integration

Emotion recognition

Cloud database for face storage

Mobile app integration

Accuracy improvement using deep learning models

