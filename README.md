# FLASK_test

FLASK installed in bioinformatics test server 10.56.46.59
First create a venv or virtual environment with python3.6.8
  python3.6 -m venv flask
Put the source of new virtual environment in path with source
  source flask/bin/activate
Make the basic FLASK script in this case, shopping.py
Run in terminal
  FLASK_APP=shopping.py flask run --host=0.0.0.0

pip install httpie
http GET http GET http://10.56.46.59:5000/api/items

