# Introduction

| Variable | Value |
| --- | --- |
| Name | Abhishek Ramesh Gadekar |
| Institute | Indian Institute of Technology, Jodhpur |
| Department | Elecrtical Engineering |
| Graduation Year | 2024 |
| Email | gadekar.1@iitj.ac.in |

# Are You Working? 😉
Facial Recognition for verifying if the correct individual is taking test, verifying if he logged in and logged out during the correct peroid. This can be used for monitoring purposes and for identification purposes.

![abhi](https://user-images.githubusercontent.com/77354191/198884308-8ca7ae45-3e12-4a18-b849-7094018695a2.jpeg)

# How It Works?


# System Design :
            A cross-platform app was developed using PyQt5, Python, OpenCV , Face_Recognition & Qt-Designer

####  ```The AI functionality of face_recognition was implemented in the backend.  The functionality was implemented in the backend because using it one can make necessary logic implementations to do the correct prediction .```

### 1. Frontend : PyQt5 & Qt-Designer ( to develop cross platform functional GUI)

### 2. Backend : Python, OpenCV , Face_Recognition , other libraries



# Packages required to run :
1. ```pip install dlib==19.18.0``` (the newwer version may create errors)
2. ```pip install face-recognition```
3. ```pip install opencv-python```
4. ```pip install numpy```
5. ```pip install PyQt5``` (check below if working on M1 mac for installation)

# Steps to Run the Application:
1. Clone the repository and open the project in pycharm and run the mainwindow.py and/before install all the necessary packages stated above. (for windows or intel based macs, m1 mac users please download intel based pycharm and run the mainwindow.py file)

# Steps to Run the Appplication on M1-Mac:

```Pro Tip: I just got know to that you can install intel version of pycharm (slower but better, no packages break) on M1 mac and run the code without any virtual environments or face any difficult in installing pyqt5 after working all the way with m1 pychaerm xd.``` 

OR 

1. Open terminal with Rosetta 2 (See here : https://dev.to/courier/tips-and-tricks-to-setup-your-apple-m1-for-development-547g)
2.  ```/usr/bin/python3 -m venv env``` Create virtual environment using non-brew python ( mine was in /usr/bin/python3)
3.  ```source env/bin/activate``` Activate the environment 
4.  ```pip install --upgrade pip``` Upgrade pip 
5.  ```pip install PyQt5``` Install PyQt5 
6.  ```python3 mainwindow.py``` Voila install other packages and run the application: 




# Future scope of the project: 
The current model doesnt ditinguish between a photo and real person and thus can be easily fooled. It can be resolved mostly by implementing a full body detection algorithm.
