🚗 Driver Drowsiness Detection System
📌 Overview

The Driver Drowsiness Detection System is a real-time computer vision application designed to detect driver fatigue and prevent road accidents. The system monitors the driver's eye movements using a webcam and identifies drowsiness based on eye closure.

🎯 Objective
To detect the driver’s face and eyes in real-time
To monitor eye closure using Eye Aspect Ratio (EAR)
To alert the driver when signs of drowsiness are detected
🧠 Key Concept

The system uses Eye Aspect Ratio (EAR) to determine whether the driver's eyes are open or closed.
If the EAR value falls below a certain threshold for consecutive frames, the system detects drowsiness.

⚙️ Technologies Used
Python
OpenCV
dlib
NumPy
SciPy
🏗️ Project Structure
Driver-Drowsiness-Detection/
│
├── detect.py
├── shape_predictor_68_face_landmarks.dat
├── requirements.txt
├── README.md
├── report.pdf
└── screenshots/
    ├── normal.png
    ├── drowsy.png
    ⚠️ Challenges Faced
Detection accuracy affected by lighting conditions
Difficulty detecting eyes when wearing glasses
Camera angle sensitivity
🚀 Future Improvements
Add alarm sound for alerts
Implement yawning detection
Use deep learning models for better accuracy
Deploy system in real vehicles
