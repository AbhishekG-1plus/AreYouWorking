# Introduction

| Variable | Value |
| --- | --- |
| Name | Abhishek Ramesh Gadekar |
| Institute | Indian Institute of Technology, Jodhpur |
| Department | Elecrtical Engineering |
| Graduation Year | 2024 |
| Email | gadekar.1@iitj.ac.in |

# Are You Working? 😉
Facial Recognition for verifying if the correct individual is taking test or doing work for certain peroid of time in todays world of post pandemic where remote work culture and online tests have prevailed . This can be used for monitoring purposes and verifying the individual.
<img width="952" alt="Screenshot 2022-10-29 at 2 03 44 PM" src="https://user-images.githubusercontent.com/77354191/198822126-4ce5d672-ff7c-4269-99db-2c5cc3ecfab5.png">

# System Design :
```The AI functionality of face_recognition was implemented in the frontend. My code is an amalgam of frontend and backend and there is no seperate line seperating the two due to the choice of technologies , languages and frameworks I used.```

## 1. Frontend : PyQt5 , Qt-Designer & Python was used to develop a complete cross-platform application.

## 2. Backend : Backend (or logic) was written in python and open-cv libraries were used to do the face-recognition and check in and check out.



# Packages required to run :
1. ```pip install dlib==19.18.0``` (the newwer version may create errors)
2. ```pip install face-recognition```
3. ```pip install opencv-python```
4. ```pip install numpy```
5. ```pip install PyQt5``` (check below if working on M1 mac for installation)

# Steps to Run the Application:
1. Clone the repository and open the project in pycharm and run the mainwindow.py and/before install all the necessary packages stated above.

# Steps to Run the Appplication on M1-Mac:

```Pro Tip: I just got know to that you can install intel version of pycharm (slower but better, no packages break) on M1 mac and run the code without any virtual environments or face any difficult in installing pyqt5 after working all the way with m1 pychaerm xd.```

1. Open terminal with Rosetta 2 (See here : https://dev.to/courier/tips-and-tricks-to-setup-your-apple-m1-for-development-547g)
2.  ```/usr/bin/python3 -m venv env``` Create virtual environment using non-brew python ( mine was in /usr/bin/python3)
3.  ```source env/bin/activate``` Activate the environment 
4.  ```pip install --upgrade pip``` Upgrade pip 
5.  ```pip install PyQt5``` Install PyQt5 
6.  ```python3 mainwindow.py``` Voila install other packages and run the application: 




# Future scope of the project: 
The current model doesnt ditinguish between a photo and real person and thus can be easily fooled. It can be resolved mostly by implementing a full body detection algorithm.
