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
