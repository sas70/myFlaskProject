# myFlaskProject

Source:  https://towardsdatascience.com/the-right-way-to-build-an-api-with-python-cd08ab285f8f

- ENter the virtual env venv

step 1 - python3 -m venv venv 
step 2 - . venv/bin/activate
step 3 - flask run


- For the imports 

pip install flask-restful 
Flask-RESTful requires Python version 2.7, 3.4, 3.5, 3.6 or 3.7

- Application Discovery Behavior

To run the application, use the flask command or python -m flask. Before you can do that you need to tell your terminal the application to work with by exporting the FLASK_APP environment variable:

As a shortcut, if the file is named app.py or wsgi.py, you don’t have to set the FLASK_APP environment variable. See Command Line Interface for more details.

$ export FLASK_APP=hello
$ flask run


