# Smile-detection-Javascript-and-flask
This project of Computer Vision aims to detect automatically a smile on human face.

The model was created on python Tensorflow and trained with a million images datasets.  (https://github.com/sandramahefa/Smile-detection-CNN-MODEL.git)

To launch the web application. It's neccessary to install flask on a python virtual environnement.(Make sure that your compter have a python already installed)

Installation step:

Launch these commands:

1) ->git clone https://github.com/sandramahefa/Smile-detection-Javascript-and-flask.git

2) ->cd Smile-detection-Javascript-and-flask

3) Install virtualenv on Linux:

->sudo apt install python-virtualenv #(Debian/Ubuntu)

or

->sudo yum install python-virtualenv #(RHEL)

or 

->py -2 -m pip install virtualenv #(Windows)
  
4) Create an Environment

->python3 -m venv flask_env #(Linux)

or

->py -3 -m venv flask_env #(Windows)
  
5) Activate the Environment

-> flask_env/bin/activate #(Linux)

or

-> \Scripts\activate #(Windows)
  
6) Install Flask

-> pip install flask

->pip install flask_socketio
 
7) Launch the application

-> python web_main.py (Linux)

or

-> Python web_main.py (Windows)
 
 
Thanks :-)
