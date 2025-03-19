﻿# orbitalbite

This code based on Python 3.10.11, check if it is installed on your computer
python --version
Output: Python 3.10.11

If it is not installed, or different version installed, change the version or use virtual environment.
Python 3.10.11 -> https://www.python.org/downloads/release/python-31011/

Check installed python version in your computer:
py -0

If you have python 3.10.11 follow steps below to create virtual environment in your directory
You should be in this folder:
![image](https://github.com/user-attachments/assets/07a76166-4fda-4de9-94a5-6ec7d4c0fc78)
![image](https://github.com/user-attachments/assets/e28d557b-c029-47ad-ae7d-5701c8efc1b6)

In this link:https://code.visualstudio.com/docs/python/environments
Follow: Using the Create Environment command steps

Select requirements.txt to install dependencies

Activate virtual environment:
.\.venv\Scripts\activate

Verify installed python version
python --version
Output should be 3.10.11

Create database
python manage.py makemigration
python manage.py migrate

Run test server to view webpage:
python manage.py runserver
Click in terminal o go to: http://127.0.0.1:8000/
