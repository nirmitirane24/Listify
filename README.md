# Listify
Python-Flask Static Web App Created with Python, SCSS, CSS and HTML

# Features

Signup and User Authentication with OTP ( SMS )
Twilio API for messaging
Task Reminder through Message ( SMS )
Verification of Phone Number through SMS
CRUD operations can be performed on Tasks, Notes
Excel sheet can be imported as tasks
Serverless Model
Inc. of Exception Handling

# Get Started
1. Create virtual enivroment with terminal in the folder where project is stored :
'''
  Set-ExecutionPolicy -ExecutionPolicy Bypass -Scope Process -Force
  ./env/Scripts/activate.ps1
'''

2. install all dependencies in virtual env

    >>> pip install flask 
    >>> pip install flask_sqlalchemy
    >>> pip install hashlib
    >>> pip install twilio.rest
    >>> pip install pandas
    >>> pip install plyer
    >>> pip install password_strength
  
 3. Create a twilio account which gives required auth and token
 
 4. Run "run.py" file and host it locally on "http://127.0.0.1:5000"
