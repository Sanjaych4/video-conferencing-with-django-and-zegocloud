# **Video Calling Application with Django and Zego Cloud**

This is a video calling application built using the Django web framework and the Zego Cloud SDK. The application allows users to create virtual rooms where they can communicate with other users through video and audio calls.

---

## Features:
- User authentication and registration
- Creation of virtual rooms by authenticated users
- Joining of virtual rooms by authenticated users
- Real-time video and audio communication through the ZegoCloud SDK
- Chat functionality during video calls

---
## Requirements:
- Python 3.x
- Django 3.x
- Zego Cloud SDK

---

## Installation:
- Clone this repository to your local machine.
- Install the required dependencies using pip:
```
pip install -r requirements.txt
```
- Sign up for a Zego Cloud account and obtain your AppID and Server Sercret key.
- Run the following command to create the database:
```
python manage.py migrate
```
- Add the AppID and the Server Secret key in `videoconferencing_app/templates/videocall.html` in their respective fields.
- Start the server by running the following command:
```
python manage.py runserver
```
- Open your web browser and navigate to http://localhost:8000 to access the application.

---

## Usage:
- Register a new account or log in to an existing one.
- Click the "Create Room" button to create a new virtual room.
- Share the room link with other users who you want to join the room.
- Click the "Join Room" button and enter the room code to join an existing room.
- Use the on-screen controls to start and stop your camera and microphone, as well as to chat with other users in the room.

--- 
 
## Demo:

![Demo](/demo.gif)