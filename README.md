# Face-Liveness
Active Liveness Detection of face using Eye Blink and Face Orientation detection.

This model is able to detect live face by calculating ROLL, PITCH, and YAW of the face.


![Demo](Orientation.png)

ROLL, PITCH, and YAW of the face are detected using a pre-trained deep learning model(Trained on Amazon’s Face Detection API ). The model uses Dlib facial landmark model to find 68 facial keypoints that are then feed to the model to find the ROLL, PITCH, and YAW of the user face.

![Demo](Face_Landmarks.png)

Required Models: https://drive.google.com/drive/folders/1BLgnnZBuq7sJOIZz6eIKnkLDbVDOvDYn?usp=sharing


Reference:https://medium.com/analytics-vidhya/face-pose-estimation-with-deep-learning-eebd0e62dbaf
