# Computer-Vision-on-Drone
 BUPT-QMUL Joint Program project repository
 
 This repository contains a model implemented on the drone aiming to recognize specific faces with real time video recorded by drone.
 
 The code is able to identify faces under different illumination conditions (bright or dim) and with different angles of the face (side or front).
 
 ## Compatibility
 The code is tested using OpenCV under MacOS 10.13.5 with Python 3.7.4.
 
 ## Dataset
 The [dataset](https://github.com/jp-drone/Computer-Vision-on-Drone/tree/master/data) has been used for training. 
 
 This training set consists of total of 1000-1200 images of 5 identifiers (around 200 pictures for each identifier). 
 
 ## Training Model
 Currently, the best results are achieved by training the model [face_recognition](https://github.com/jp-drone/Computer-Vision-on-Drone/tree/master/face-recognition-opencv).
 
 This model refers to previous accomplished model. More details can be found on [pyimagesearch](https://www.pyimagesearch.com/2018/06/18/face-recognition-with-opencv-python-and-deep-learning/) and [GitHub](https://github.com/ageitgey/face_recognition)
