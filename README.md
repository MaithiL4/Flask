# Flask
Flask
Learning Flask from basics 

Flask is a micro web framework written in Python. It is classified as a micro framework because it does not require particular tools or libraries.It has no database abstraction layer, form validation, or any other components where pre-existing third-party libraries provide common functions. However, Flask supports extensions that can add application features as if they were implemented in Flask itself. 

Applications that use the Flask framework include Pinterest and LinkedIn.

For each project we can't use the same version of Technology so we have to create environment for projects so we can install multipule varsion of  packages that we need.
Type a command : - virtualenv env

now we have to activate the enviroment. :- .\env\Scripts\activate.ps1

We need to Install Flask First. In terminal type :- pip install flask.

now create a file name as app.py
we need to create A minimal APP go to google and type flask minimal and copy the code of 5 lines. and past it into app.py

code:- 

from flask import Flask
app = Flask(__name__)

@app.route('/')
def hello_world():
    return 'Hello, World!'
# now run the  app 
if __name__ == "__main__":
    app.run(debug=True) #this will show the error in the browse.
    
now in terminal type :- python .\app.py to run 
our first app is Ready.

out put on browser  :- Hello, World!
