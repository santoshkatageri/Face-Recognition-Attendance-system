# Face-Recognition-Attendance-system
The "Face recognition attendance system" is a hardware prototype of a face recognition attendance system. This project is developed using Rasberry pi, RPI camera , OpenCV and Python coding.

The project carried out with the help of the resources and links mentioned below -

Installation of OpenCV (Open source Computer Vision project) on raspberry pi B+ using the instructions given in below links
http://www.pyimagesearch.com/2015/02/23/install-opencv-and-python-on-your-raspberry-pi-2-and-b/
 
I used the AT&T laboratory's Face database approach to create our Face database.This link will give you more details
http://www.cl.cam.ac.uk/research/dtg/attarchive/facedatabase.html

I refered "Raspberry Pi Face Recognition Treasure Box" project to learn basics of face recognition project.
http://makezine.com/projects/pi-face-treasure-box/

The "face recognition attendance system" have-
-Raspberry Pi b+
-RPI camera module
-Computer monitor(For display puspose)
-Python GUI application is developed to provide user interface

The face recognition attendance system works as follows- 
when the complete set up is made and My_attendancesystem.py is Running, User has to enter the details by clocking "New member" button in Python GUI applicationwhich takes the details like name ,gender ,email id, mobile number and save it to the "DetailsDatabase.csv".

For recognition ,system needs to be trained with the user's faces. To train the system user should click the button in "Train Recognizer". This will capture the images of the user and creates a folder in "training" folder like 

/training
Positive/
User/
--------001.pgm
--------002.pgm

when the user want to marks his/her attendance , should clock the button "Mark attendance"
It will capture the image of the user and make some operations on the face image and compare it in the face database and if found attendance will be marked.

For user to know about the attendance, "check attendannce" and "mail my attendance" buttons are used.



Note:
The “Face recognition attendance system” based on image processing in SIT Tumkuru, as a part of the prescribed curriculum.

-The project developed using RPI image sensors, Raspberry Pi, OpenCV libraries, and Python programming for the successful completion of the project.

-The project aimed at developing a hardware prototype for the face recognition attendance system.

-Got 2nd “BEST PROJECT” Prize for major Project in Branch Project exhibition.
