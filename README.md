# pythoncrud
Python CRUD


# Installation

pip3 install flask
pip3 install flask-mysqldb


from flask import Flask
app=Flask(__name__)

# Loading Home Page
@app.route("/")
def home():
	return '<h1>Hello World</h1>';

if(__name__=='__main__'):
	app.run(debug=True);

python3 app.py

http://127.0.0.1:5000/


#Kill Mode

ps -ef | grep python

sudo kill -9 -30345

