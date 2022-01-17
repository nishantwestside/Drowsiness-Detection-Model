**Drowsiness Detection Model**

With this Python project, we will be making a drowsiness detection system. A countless number of people drive on the highway day and night. Taxi drivers, bus drivers, truck drivers and people traveling long-distance suffer from lack of sleep. Due to which it becomes very dangerous to drive when feeling sleepy.

The majority of accidents happen due to the drowsiness of the driver. So, to prevent these accidents we will build a system using Python, OpenCV, and Dlib which will alert the driver when he feels sleepy.




**Driver Drowsiness Detection System-**

Step 1 – Take image as input from a camera.

Step 2 – Detect the face in the image and create a Region of Interest (ROI).

Step 3 – Detect the eyes from ROI and feed it to the classifier.

Step 4 – Classifier will categorize whether eyes are open or closed.

Step 5 – Calculate score to check whether the person is drowsy.




**BASIC REQUIREMENTS-**

Python 3.X (all version except 3.10)
OS : Windows 7/8/10, Mac, Linux
GPU required for fast processing (Min. 512 MB)
Web-Cam (Recommended)


IDE : Visual Studio & Visual Studio Code
Command Prompt
Cmake (for Dlib) (Recommended)


Modules used or are required to run this Project :

OpenCV
Dlib 
SciPy
Pygame



**Driver Drowsiness Detection Dataset**

The dataset used for this model is created by us. To create the dataset, we wrote a script that captures eyes from a camera and stores in our local disk. We separated them into their respective labels ‘Open’ or ‘Closed’. The data was manually cleaned by removing the unwanted images which were not necessary for building the model. The data comprises around 7000 images of people’s eyes under different lighting conditions. After training the model on our dataset, we have attached the final weights and model architecture file “models/cnnCat2.h5”.

Now, you can use this model to classify if a person’s eye is open or closed.


![image](https://user-images.githubusercontent.com/77064606/149773040-27358f77-a006-4ea5-a2f5-e5dab6685359.png)




**PRINCIPLE OF DDM**

The driver drowsiness detection is based on a Dlib, which begins recording the driver’s conscious behaviour the moment the trip begins.

Dlib has excellent Face Detection and Face Landmark Detection algorithms built-in.

It provides pre-trained models for face landmark detection.

The shape_predictor_68_face_landmarks.dat file is the pre-trained Dlib model for face landmark detection.




**WORKING FLOW-**

![image](https://user-images.githubusercontent.com/77064606/149773394-f0f9725b-af9e-4bec-89f9-138f2523f4fa.png)




**OUTPUTS-**

![image](https://user-images.githubusercontent.com/77064606/149773504-6e1f4aba-240e-431a-9a4f-c1655bc574ac.png)
STATE 1 - WHEN EYES ARE OPEN


![image](https://user-images.githubusercontent.com/77064606/149773588-f3e3a6eb-45dd-4e09-b2c4-bf22ce04d976.png)
STATE 2 - WHEN EYES ARE CLOSED




**BIBLIOGRAPHY-**

www.stackoverflow.com
www.dlib.net
www.github.com
