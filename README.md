# Introduction

| Variable | Description |
| --- | --- |
| Name | Abhishek Ramesh Gadekar |
| Institute | Indian Institute of Technology, Jodhpur |
| Graduation Year | 2024 |
| Email | gadekar.1@iitj.ac.in |

# Are You Working?
Facial Recognition for verifying if the correct individual is taking test or doing work . This can be used for monitoring purposes and verifying the individual.


# Packages required to run :
1. ```pip install dlib==19.18.0```
2. ```pip install face-recognition```
3. ```pip install opencv-python```
4. ```pip install PyQt5``` (check below if working on M1 mac for installation)

# Steps to Run the Application:
1. Clone the repository and open the project in pycharm and run the mainwindow.py and/before install all the necessary packages stated above.

# Steps to Run the Appplication on M1-Mac:
1. Open terminal with Rosetta 2 (See here : https://dev.to/courier/tips-and-tricks-to-setup-your-apple-m1-for-development-547g)
2.  ```/usr/bin/python3 -m venv env``` Create virtual environment using non-brew python ( mine was in /usr/bin/python3)
3.  ```source env/bin/activate``` Activate the environment 
4.  ```pip install --upgrade pip``` Upgrade pip 
5.  ```pip install PyQt5``` Install PyQt5 
6.  ```python3 mainwindow.py``` Voila install other packages and run the application: 




# Future scope of the project: 
The current model doesnt ditinguish between a photo and real person and thus can be easily fooled. It can be resolved mostly by implementing a full body detection algorithm.
