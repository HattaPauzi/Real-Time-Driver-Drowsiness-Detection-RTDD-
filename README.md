This project is based on the research paper "Real-time Driver Drowsiness Detection for Android Application Using Deep Neural Networks Techniques" by Rateb Jabbar et al. published in Procedia Computer Science in 2018. The aim of this project is to implement the proposed approach for real-time driver drowsiness detection on an Android application using deep neural networks techniques.

The proposed approach consists of five steps: extracting videos from the NTHU database, extracting images from video frames, extracting landmark coordination from images using the Dlib library, preparing a deep learning model based on facial landmark key point detection, and evaluating the state or level of drowsiness of the driver.

The Android mobile camera is used to take facial pictures of the driver, which are then transferred to the Dlib library for facial landmark detection. The collected data is then passed to the driver drowsiness detection algorithm based on the trained model, which evaluates the state or level of drowsiness of the driver. If the result indicates drowsiness, the application signals the driver with visual and audio messages.

The dataset used for training and testing consists of videos of 18 subjects from the NTHU database, recorded in five simulated driving scenarios. The proposed model is able to achieve an accuracy of more than 80%.

This project includes the implementation of the proposed approach on an Android application using deep neural networks techniques. The code is written in python language, and the Dlib library is used for facial landmark detection. The project can be used as a tool for real-time driver drowsiness detection, which can contribute to improving road safety and preventing accidents.
