# python-flask
```
py -3.11 -m venv .venv
```
```
source .venv/Scripts/activate
```
```
flask run
```
### app.py
```
from flask import Flask  
  
app = Flask(__name__) #creating the Flask class object   
 
@app.route('/') #decorator drfines the   
def home():  
    return "hello, this is our first flask website";  
  
if __name__ =='__main__':  
    app.run(debug = True)
```
