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





## Screenshots 

<img src="https://user-images.githubusercontent.com/106477200/170887133-3c427ce1-f7de-443b-9c90-de0baac9adb5.png" width="45%"></img>
<img src="https://user-images.githubusercontent.com/106477200/170887136-cb3c04a3-867c-4cfc-98d1-031dd5816ea4.png" width="45%"></img>
<img src="https://user-images.githubusercontent.com/106477200/170887138-de03f832-0e92-4498-9375-3903c622d144.png" width="45%"></img>
<img src="https://user-images.githubusercontent.com/106477200/170887139-7f6c0a13-d722-4d5d-a6d2-ff120d0a7c58.png" width="45%"></img>
<img src="https://user-images.githubusercontent.com/106477200/170887142-6aa66d7a-a7e3-45b3-bb42-a5c91aeac8da.png" width="45%"></img>
<img src="https://user-images.githubusercontent.com/106477200/170887143-6a888f4c-8ad9-4a52-aab8-7c8867d298e8.png" width="45%"></img>
<img src="https://user-images.githubusercontent.com/106477200/170887144-a82455a4-be57-4c98-876c-af8698d022d2.png" width="45%"></img>
<img src="https://user-images.githubusercontent.com/106477200/170887145-d6b08124-e859-4343-987a-bf46d8da1ef4.png" width="45%"></img>
<img src="https://user-images.githubusercontent.com/106477200/170887147-259e37e4-883b-4f45-9774-f05222ac1645.png" width="45%"></img>
<img src="https://user-images.githubusercontent.com/106477200/170887151-fc43a35f-daf8-4bb5-8dff-eb4f79b313fa.png" width="45%"></img>
<img src="https://user-images.githubusercontent.com/106477200/170887154-62d35cf8-9d85-431b-b848-796e41767af2.png" width="45%"></img>
<img src="https://user-images.githubusercontent.com/106477200/170887156-2c79a444-ee80-4584-94da-560588875c80.png" width="45%"></img>
<img src="https://user-images.githubusercontent.com/106477200/170887159-93a83c22-6e39-4145-93eb-9381e53accea.png" width="45%"></img>
<img src="https://user-images.githubusercontent.com/106477200/170887161-29bd75f4-bc98-4a34-a589-90f0c7ccb713.png" width="45%"></img>
<img src="https://user-images.githubusercontent.com/106477200/170887164-5921fca3-ad2a-4d98-bdf4-bcee958178ba.png" width="45%"></img>
<img src="https://user-images.githubusercontent.com/106477200/170887167-17f2bcee-14d9-4f28-b3fa-4542e039045a.png" width="45%"></img>
<img src="https://user-images.githubusercontent.com/106477200/170887171-13bb65c7-bcf3-4595-8454-34f4aebd76b0.png" width="45%"></img>


