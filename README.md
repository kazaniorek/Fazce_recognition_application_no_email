
# Face Recognition App (No Email Alerts)

This project implements a simplified real-time face recognition application using OpenCV and face_recognition libraries. 
Unlike the extended version, this version does not include email alerts, making it ideal for local/offline usage and demonstration purposes.

## Features

- Real-time face detection and recognition using a webcam
- Displays recognised faces directly on the video feed
- Supports custom training images of known individuals

## Technologies

- Python
- OpenCV
- face_recognition
- NumPy

## How to Run

1. Install the required libraries:
   ```bash
   pip install opencv-python face_recognition numpy
   ```

2. Place reference images of known individuals in the appropriate directory (as defined in the notebook).

3. Run the notebook:
   - `Face_recognition_app_with_alert_emails.ipynb`  
     *(Note: Despite the filename, this version does not send emails.)*

## Author

Mariusz Sołtycz

---

This version was developed during my BSc Artificial Intelligence degree as a lightweight face recognition demonstration without alert functionality.
