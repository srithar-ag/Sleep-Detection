# Real-Time Sleep (Eye-closed, it alarms) Detection System

A real-time computer vision–based drowsiness detection system that monitors eye movements using facial landmarks and triggers an audio alert when prolonged eye closure is detected.

This project is designed as a **Digital Image Processing (DIP) / Computer Vision mini-project** and works smoothly on macOS using a Conda-based Python environment.

---

## 🚀 Features

- 🎥 Real-time webcam video processing  
- 👁️ Eye Aspect Ratio (EAR)–based drowsiness detection  
- 🧠 Facial landmark detection using dlib (68-point model)  
- 🔔 Non-blocking audio alert on prolonged eye closure  
- ⚡ Lightweight and fast execution  
- 🖥️ Works reliably on macOS  

---

## 🛠️ Tech Stack

- **Python 3.8**
- **OpenCV** – video capture & image processing
- **dlib** – face detection & facial landmarks
- **imutils** – utility functions for vision tasks
- **NumPy & SciPy** – numerical computations
- **simpleaudio** – reliable cross-platform audio alerts

---

## 📂 Project Structure

## Drowsiness-Detection/
 ├── detect_drowsiness.py
 
├── shape_predictor_68_face_landmarks.dat
 
 ├── alarm.wav
 
 ├── requirements.txt
 
 ├── README.md
 
 └── assets/

## Required Downloads

```
shape_predictor_68_face_landmarks.dat from official site for dataset
``` 

## Acknowledgements

- dlib facial landmark model

- OpenCV community

- imutils by Adrian Rosebrock
