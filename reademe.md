# first my code with flask
-----

I am a beginner in flask
I decided to share my first code  and experience with you
u
---
lets go for install flask

### Flask installation steps
We must first provide the prerequisites


 
 First we have to install the virtual environment to have an isolated environment
 #### 1. Virtual environment installation
 
***linux***
``` sh 
    $ Pip3 install virtualenv –user 
```
 ***windows***
``` sh
    $ pip install virtualenv
```

    
#### 2. Create a folder or directory at the address you want
``` sh 
    $ mkdir yournamedirectory
```
In ***Linux*** and ***windows*** we go to the directory address
``` sh
    $ Cd ./yournameddirectory
```

In Linux, we enter the following code into the directory address to use the virtual environment

***linux***
```
    $ Python3 virtualenv venv
```
***windows***
```
    $ py -3 -m virtualenv venv
```

#### 3.Activation of virtual environment
I enter the following command to activate

***linux***
```
    $ Source env/bin/activate
```

***windows***
```
    $ .\venv\script\activate
```
In Linux and Windows, when the virtual environment is activated, the word **<venv>** appears at the beginning of the command line.

### 4.now we can install flask
To install Flash in ***Linux*** and ***windows***, we use the following command
```
    $ pip install flask  
```



                        *****Finally we installed Flask*****
                        
Now we run the flask code using vccode

```
from flask import Flask
app = Flask(__name__)

@app.route('/')
def hello_world():
    return 'Hello World!'

if __name__ == '__main__':
    app.run()
```
After executing the code we have a url that runs on port   **5000**
Well, the first code  which is *****hello world***** displayed on the browser page

    
    



