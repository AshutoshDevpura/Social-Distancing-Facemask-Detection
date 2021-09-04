## About The Project
MDD Project for SRM Institute of Science and Technology.

This Repository contains two tools, first to detect if a person is wearing a Face mask or not, and second, to see if Social distancing is maintained or not in real-time using pre-installed surveillance cameras.


### Face Mask Detection
Face Mask Detection system built with OpenCV, Keras/TensorFlow using Deep Learning and Computer Vision concepts in order to detect face masks in static images as well as in real-time video streams.



### Social Distancing Detection
Social Distancing Detection tool to monitor social distancing from CCTV, videos using Python, Deep Learning, Computer Vision. This tool can automatically estimate the interpersonal distance from uncalibrated RGB cameras. Can be used at public places and workplace.




## Getting Started 

### Clone
```
git clone https://github.com/AshutoshDevpura/Social-Distancing-Facemask-Detection
```

### Prerequisites 
1. ![Python](https://img.shields.io/badge/python-v3.6+-blue.svg)

2. ![pip3](https://img.shields.io/badge/pip-v21.0+-blue.svg)


### Installation
#### Face Mask Detector:
1. download the data set from the given link.
https://drive.google.com/drive/folders/16YbYg8usZtSXn1_edpdBR0susFstwLrr?usp=sharing.
2. mv the data set into Face_Mask_Detector folder.
3. cd Face_Mask_Detector.
3. Install virtual environment. 
  ``` 
  pip3 install virtualenv
  ```
5. Create the virtual environment.
  ```
   virtualenv env_name
  ```
 6. Download all requirements from requirements.txt.
  ```
  pip3 install -r requirements.txt
  ```
7. Run detect_mask_video.py.
  ```
   python3 detect_mask_video.py  
  ```


#### Social Distancing Detector:
1. download the yolo weights from the given link
https://pjreddie.com/media/files/yolov3.weights.
2. mv the yolo weights into Social Distancing Detector folder.
3. cd Social_Distancing_Detector.
3. Install virtual environment. 
  ``` 
  pip3 install virtualenv
  ```
5. Create the virtual environment.
  ```
   virtualenv env_name 
  ```
 6. Download all requirements from requirements.txt.
  ```
  pip3 install -r requirements.txt
  ```
7. Run social_distancing_analyser.py.
  ```
  python3 social_distancing_analyser.py
  ```
  
  ## Output
  
  ### Face Mask Detector 
  
  ![image](https://user-images.githubusercontent.com/46817661/114898178-8364b980-9e2f-11eb-8e85-79ba5b8ea1ab.png)
  #### Detection of an Unmasked Individual
  
  ![image](https://user-images.githubusercontent.com/46817661/114898559-d50d4400-9e2f-11eb-8eae-06a895e1fe78.png)
  #### Detection of a Masked Individual 
  
 <br>
 
  ### Social Distancing Detector 
  
  ![image](https://user-images.githubusercontent.com/46817661/114898880-21f11a80-9e30-11eb-8f2b-fb954ab1a685.png)
  #### ROI of Social Distancing Detector
  
  ![image](https://user-images.githubusercontent.com/46817661/114899021-41884300-9e30-11eb-89a0-324a2e693472.png)
 #### Social Distancing Detection 
  
 ## Conference Paper
 https://ieeexplore.ieee.org/document/9315934
