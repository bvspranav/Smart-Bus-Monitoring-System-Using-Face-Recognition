# Smart-Bus-Monitoring-System-using-face-recognition

This repository contains code for a real-time face recognition system utilizing FaceNet, MTCNN, and Google Sheets integration. The system aims to recognize faces, determine fee payment status, and monitor student boarding times for a school or educational institution's bus monitoring system.

## Abstract

The Real-time Face Recognition Using FaceNet project presents a comprehensive system designed to facilitate efficient monitoring and management of student boarding activities for educational institutions, specifically focusing on bus monitoring systems. Leveraging state-of-the-art facial recognition technology and integrations with Google Sheets and Telegram, this system automates the identification of students, tracks their fee payment statuses, and monitors their boarding times.

## Project Overview
The system performs the following key functionalities:

Face Detection and Recognition: Utilizes the MTCNN (Multi-Task Cascaded Convolutional Neural Network) for face detection and FaceNet for face recognition.
Google Sheets Integration: Enables storing student information, including names, fee statuses, and boarding times, in Google Sheets for tracking and management.
Telegram Bot Integration: Provides real-time notifications and communication via a Telegram bot for alerts and updates on student boarding activities.

## Requirements

To run this project, ensure you have the following prerequisites installed:

#### Python 3.x
#### OpenCV
#### TensorFlow
#### mtcnn
#### NumPy
#### SciPy
#### Google API Python Client
#### gspread
#### Telepot
#### oauth2client
#### Openpyxl


## Usage

### Set Up Google Sheets Credentials:
Obtain and set up a Google Sheets API credential JSON file.
Update the path in the code to the JSON file in ServiceAccountCredentials.from_json_keyfile_name.

### Prepare Student Data:

Ensure an Excel file named student_data.xlsx exists or create one.
Populate the file with columns: Student Names, Fee Statuses, and Boarding Times.

### Telegram Bot Configuration:

Obtain a Telegram bot token and replace 'YOUR_TELEGRAM_BOT_TOKEN' with the actual token in the code.
Set up and configure Telegram bot functionalities as needed.

### Face Recognition Setup:

Prepare face encodings using FaceNet and store them in a .pkl file.
Update the paths for the FaceNet model, encoding file, and other necessary paths.

### Run the System:

Execute the main Python script main.py to start the real-time face recognition system.

### Interacting with the System:

The system will open the camera, detect faces, recognize students, and display notifications via Telegram.
Based on recognized faces, fee statuses, and boarding times, the system updates Google Sheets and sends alerts.

Replace placeholders such as YOUR_TELEGRAM_BOT_TOKEN, Maintainer's Name, and email@example.com with appropriate details. Additionally, ensure to include the necessary instructions and prerequisites based on your specific setup and requirements.


## Conclusion:
The Real-time Face Recognition Using FaceNet project offers an efficient and automated solution for monitoring student boarding activities in educational institutions. By integrating advanced face recognition technology with Google Sheets and Telegram, this system streamlines administrative tasks, enhances security measures, and facilitates real-time communication, thereby contributing to improved management of student transportation systems.
