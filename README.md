# Attendance-based-on-Face-Recognition
I have developed this website using HTML and Python


This project involves building an attendance system which utilizes facial recognition to mark the presence, time-in, and time-out of employees. It covers areas such as facial detection, alignment, and recognition, along with the development of a web application to cater to various use cases of the system such as registration of new employees, addition of photos to the training dataset, viewing attendance reports, etc. This project intends to serve as an efficient substitute for traditional manual attendance systems. It can be used in corporate offices, schools, and organizations where security is essential.

This project aims to automate the traditional attendance system where the attendance is marked manually. It also enables an organization to maintain its records like in-time, out time, break time and attendance digitally. Digitalization of the system would also help in better visualization of the data using graphs to display the no. of employees present today, total work hours of each employee and their break time. Its added features serve as an efficient upgrade and replacement over the traditional attendance system.

**The system mainly works around 2 types of users**
1. Employee
2. Admin

**Following functionalities can be performed by the admin: <br>**
• Login <br>
• Register new employees to the system <br>
• Add employee photos to the training data set <br>
• Train the model <br>
• View attendance report of all employees. Attendance can be filtered by date or employee. <br>

**Following functionalities can be performed by the employee: <br>**
• Login <br>
• Mark his/her time-in and time-out by scanning their face <br>
• View attendance report of self <br>

## Face Detection
Dlib's HOG facial detector.

## Facial Landmark Detection
Dlib's 68 point shape predictor

## Extraction of Facial Embeddings
face_recognition by Adam Geitgey

## Classification of Unknown Embedding 
using a Linear SVM (scikit-learn)


## How To Run ?
- clone it on your computer
- make a separate [python virtual environment](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/) or use the default one already installed on your machine
- Download [this](https://drive.google.com/uc?export=download&id=1HzO-rnEqgkZ6tLt48yWhYgHk1_zOIYhf) file 
 - put it inside **``` \Attendance-based-on-Face-Recognition\face_recognition_data ```** directory
- run **``` pip install -r requirements.txt inside \Attendance-based-on-Face-Recognition ```** directory
- Run **``` python manage.py runserver ```** inside **``` \Attendance-System-Using-Face-Recognition ```** directory to run the project
- Enjoy !
