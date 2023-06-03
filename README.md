
# 😷 Face Mask Detection System 😷

A face mask detection is a system that is capable of detecting if one or more individuals is wearing a face mask. This project recognizes and displays the number of faces detected, the number of peaople wearing the face mask correctly, incorrectly or not in a picture. With the increasing number of COVID-19 victims, it is pivotal to integrate systems capable of detecting people wearing a face mask properly or not, this will help curtail the virus. I humbly ask that we obey the rules set aside and wear face mask correctly to reduce the risk of spreading the virus.


![](mask_det.gif)  

## Acknowledgements

 - [The coronavirus disease 2019 (COVID-19) pandemic](https://www.researchgate.net/publication/340856011_The_coronavirus_disease_2019_COVID-19_pandemic)
 - [Face Mask Detector](https://www.researchgate.net/publication/344173985_Face_Mask_Detector)



## Advantages

This solution provides the following:

- Face mask detection accuracy of 94% 
- Ability to identify multiple people at once in real time.
- Ability to track and identify if the face mask is put on correctly. 

## Business Case
​
Can be used in Hospitals, Airports, Banks, Schools and Organizations 
## Technical details 

**Input 1 (video or image to process, capable of processing):** ​​

- mjpeg stream

- rtsp stream

- USB camera devices

- video files (avi, mp4, mkv formats supported)

- standalone image files (.png, .jpg formats supported)

 

**Input 2:**

Reference images to which the system compares the faces in the image. (.png, .jpg formats supported)


**Outputs:**

- Processed video frame

- The faces in the frame (bounding boxes) showing whether face mask is worn or not.

**For each face:**

- Unique Tracking ID (when processing a video file, the same ID on each frame belongs to the same person)

- The most similar reference face ID

- Degree of similarity to the reference face

- Up to 5 facial landmark points

- The system is able to to write the processed video to a video file. 
## Used By

This project is used by the following:

- Kaduna State University
- Daton


## Tech Stack

- Dlib, Numpy, OpenCV, Flask, Tensorflow, Keras, Pickle
## How to use 

- Clone the repo
$ git clone https://github.com/Davisonyeas/mask_detection.git

- Change your directory to the cloned repo and create a Python virtual environment named 'mask'
$ mkvirtualenv test

- Now, run the following command in your Terminal/Command Prompt to install the libraries required
$ pip3 install -r requirements.txt

👏 Congratulations
Feel free to mail me for any doubts/query ✉️ davisonyeas1@gmail.com

🤝 Contribution
Feel free to file a new issue with a respective title and description on the this mask detection repository. If you already found a solution to your problem, I would love to review your pull request!

❤️ Owner
Made by Davis Onyeoguzoro


## Connect

For support, email davisonyeas1@gmail.com

Follow me on LinkedIn, https://www.linkedin.com/in/davis-onyeoguzoro/